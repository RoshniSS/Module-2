# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
n = int(input())

for i in range(n):
    print(' ' * (n - i), end='')
    num = 1
    for j in range(i + 1):
        print(num, end=' ')
        num = num * (i - j) // (j + 1)
    print()

## Sample Output
<img width="1369" height="532" alt="Screenshot 2026-06-01 112347" src="https://github.com/user-attachments/assets/8080c0e5-34ac-4f46-9d9f-a23640d1349e" />

## Result
Thus, the Python program to generate Pascal's Triangle for the given number of rows was executed successfully, and the desired output was obtained.

