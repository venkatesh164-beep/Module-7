# 📐 Taylor Series:sinh(x) Evaluation using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate the value of **sinh(x)** for **n terms** using recursion.

---

## 🧠 ALGORITHM:

1. **Start**
2. Read input for variable `x` (angle or number)
3. Read input for variable `n` (number of terms)
4. Define a function `fact(n)`:
   - If `n <= 1`, return 1
   - Else, return `n * fact(n - 1)` (recursive factorial)
5. Define a function `sinh(x, n)`:
   - If `n == 0`, return `x`
   - Else, return `(pow(x, 2*n + 1) / fact(2*n + 1)) + sinh(x, n - 1)`
6. Call the `sinh(x, n)` function and print the result
7. **Stop**

---

## 💻 PROGRAM:
def fact(n): return 1 if n <= 1 else n * fact(n - 1)<br>
def sinh(x, n): return x if n == 0 else x**(2*n + 1) / fact(2*n + 1) + sinh(x, n - 1)<br>

x = int(input())<br>
n = int(input())<br>
print(sinh(x, n))



## OUTPUT
<img width="704" height="303" alt="image" src="https://github.com/user-attachments/assets/9c4a250f-99b0-4ab8-bf43-cca2ea2c74b1" />

## RESULT
Thus, the program has been successfully executed.
