# student-gpa-calculator
A beginner Python program that calculates student grades and GPA
print("Welcome to the GPA calculator!")
grade1 = float(input("Enter your first grade: "))
grade2 = float(input("Enter your second grade: "))
grade3 = float(input("Enter your third grade: "))
average = (grade1 + grade2 + grade3) / 3
print("Your average is:", average)
if average >= 70:
    print("You are passing!")
else:
    print("You need to improve your grade."
