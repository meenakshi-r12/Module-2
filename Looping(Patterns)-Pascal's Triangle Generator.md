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
```
import math
r=int(input())
for i in range(r):
    print(' '*(r-i),end='')
    for j in range(i+1):
        v=math.comb(i,j)
        print(v,end='')
    print()
```

## Sample Output
![Screenshot (57)](https://github.com/user-attachments/assets/32281bd7-b631-4451-8573-cc9d22da3a4d)

## Result
Thus the program is verified.
