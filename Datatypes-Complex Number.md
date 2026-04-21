# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
Add Code Here
# Program to create and display a complex number
def complex_number_demo():
    # Read two integers
    real_part = int(input("Enter the real part: "))
    imag_part = int(input("Enter the imaginary part: "))
    
    # Create complex number
    c = complex(real_part, imag_part)
    
    # Print results
    print("Complex number:", c)
    print("Real part:", c.real)
    print("Imaginary part:", c.imag)

# Driver code
complex_number_demo()


## Output
<img width="939" height="637" alt="image" src="https://github.com/user-attachments/assets/2664346f-585f-4b52-8e10-a67ab16993f2" />


## Result
