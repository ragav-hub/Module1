# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
# Get input from the user
a = int(input("Enter a number: "))

# Check if the number is even or odd
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```
## Output
```
Enter a number: 5
ODD
Enter a number: 10
EVEN
```

## Result
Thus The Code is Executed Successfully.
