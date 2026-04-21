
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
# Program to evaluate boolean and arithmetic expressions
def evaluate_expressions():
    print("True + True =", True + True)       # 1 + 1 = 2
    print("True + False =", True + False)     # 1 + 0 = 1
    print("False + False =", False + False)   # 0 + 0 = 0
    
    print("True * 5 =", True * 5)             # 1 * 5 = 5
    print("False * 5 =", False * 5)           # 0 * 5 = 0
    
    print("True == 1:", True == 1)            # True
    print("False == 0:", False == 0)          # True
    print("True and False =", True and False) # False
    print("True or False =", True or False)   # True
    print("not True =", not True)             # False

# Driver code
evaluate_expressions()


## Output
<img width="1223" height="711" alt="image" src="https://github.com/user-attachments/assets/a9f89102-14c7-42f1-ac56-b7609c5dde67" />

## Result
