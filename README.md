# Python-Grade-Checker
print("Student Grade Checker")
print("=" * 30)

#Student Data
students = ["Salim", "Karim", "Jalil", "Alam"]
grades = [85, 79, 65, 90]

#Part1: Comparison Operators (<,>,=)
print("\n Grade Analysis")
print("_" * 20)

passing_grade = 70
honor_roll = 90

#For loop with IF-ELSE
for i in range(len(students)):
    name = students[i]
    grade = grades[i]

    print(f"\nStudent: {name}")
    print(f"Grade: {grade}")

#If-Else with Comparison operators
    if grade >= honor_roll:
        status = "Honor Roll!"
        Letter = "A"
    elif grade >= 80:
        status = "Good Job!"
        Letter = "B"
    elif grade >= passing_grade:
        status = "Passing Grade!"
        Letter = "C"
    else:
        status = "Needs Help"
        Letter = "F"
    print(f"Letter: {Letter}")
    print(f"Status: {status}")
