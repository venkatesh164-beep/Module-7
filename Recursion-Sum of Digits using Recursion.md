# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
def sum_digit(n):<br>
    return 0 if n <= 0 else n % 10 + sum_digit(n // 10)<br>

n = int(input())<br>
print(sum_digit(n) if n >= 0 else "Enter valid number")



## OUTPUT
<img width="479" height="301" alt="image" src="https://github.com/user-attachments/assets/d8292bf7-3714-47cd-914e-924817feb459" />

## RESULT
Thus, the program has been successfully executed.
