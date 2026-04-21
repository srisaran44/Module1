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
# Function to check even or odd
def check_even_odd(num):
    if num % 2 == 0:
        print("The number is Even.")
    else:
        print("The number is Odd.")

# Driver code
number = int(input("Enter a number: "))
check_even_odd(number)

## Output
<img width="1187" height="750" alt="image" src="https://github.com/user-attachments/assets/50d2200b-c93c-49e6-b845-2d4a1d0102f9" />


## Result
