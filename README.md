# 🎓 Grade Checker

A simple Python program that asks the user for a numeric grade (0–100) and converts it into a letter grade (A–F).  
Includes input validation to prevent grades over 100 or below 0.

## 💡 What You'll Learn
- How to use `input()` and `int()` for user input
- `if` / `elif` / `else` conditions
- Comparison logic
- Basic input validation

## ▶️ How to Run
1. Run the script in a Python environment
2. Enter your numeric grade (0–100)
3. The program tells you your letter grade (A, B, C, D, or F)
4. If the input is invalid, it will show an error message

-----------------------------------------------------------------------

grade = int(input("Enter your grade: "))

if grade > 100 or grade < 0:
    print("Invalid Grade")
elif grade >= 90:
    print("Your grade is A")
elif grade >= 80:
    print("Your grade is B")
elif grade >= 70:
    print("Your grade is C")
elif grade >= 60:
    print("Your grade is D")
else:
    print("Your grade is F")
