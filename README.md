# program-1
name=input("enter student name: ")
roll=input("enter roll number: ")
course=input("enter course name: ")
PRINT("\nenter marks out of 100:\n")
s1=int(input("subject1:"))
s2=int(input("subject2:"))
s3=int(input("subject3:"))
s4=int(input("subject4:"))
s5=int(input("subject5:"))
total=s1+s2+s3+s4+s5
percentage=total/5
if percentage>=90:
    grade="A+"
elif percentage>=80:
    grade="A"
elif percentage>=70:
    grade="B+"
elif percentage>=60:
    grade="B"
elif percentage>=50:
    grade="C"
else:
    grade="fail"
print("\n========================STUDEBT MARKSHEET============================")
print("Name          :",name)
print("Roll Number   :",roll)
print("Course        :",course)
print("--------------------------------------------------")
print("subject1      :",s1)
print("subject2      :",s2)
print("subject3      :",s3)
print("subject4      :",s4)
print("subject5      :",s5)
print("--------------------------------------------------")
print("Total Marks   :", total)
print("Percentage    :", percentage, "%")
print("Grade         :", grade)
print("===============================================")


Output:
Enter Student Name: hanunethra
Enter Roll Number: 29
Enter Course Name: computer science

Enter marks out of 100:

Subject 1: 88
Subject 2: 90
Subject 3: 75
Subject 4: 100
Subject 5: 99

============== STUDENT MARKSHEET ==============
Name        : hanunethra
Roll Number : 29
Course      : computer science
-----------------------------------------------
Subject 1   : 88
Subject 2   : 90
Subject 3   : 75
Subject 4   : 100
Subject 5   : 99
-----------------------------------------------
Total Marks : 452
Percentage  : 90.4 %
Grade       : A+
===============================================


