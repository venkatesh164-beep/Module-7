# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
def sum_of_digits(num):<br>
    return sum(int(digit) for digit in str(num))<br>

def fun(n):<br>
    if n <= 0:<br>
        return<br>
    fun(n - 1)<br>
    print(f"Current value: {n}, Sum of digits: {sum_of_digits(n)}")<br>


num = int(input("Enter a positive integer: "))<br>

if num % 2 != 0:<br>
    num += 1<br>

print(f"Adjusted input (even number): {num}\nSequence (head recursion):")<br>
fun(num)

## OUTPUT
<img width="809" height="210" alt="image" src="https://github.com/user-attachments/assets/301700c7-d93b-4a2b-946d-4c44b3158d4c" />

## RESULT
Thus, the program has been successfully executed.
