# 🔺4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.


## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

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
n=int(input())
for i in range(n):
 print(' '*(n-i),end='')
 c=1
 for j in range(i+1):
  print(c,end=' ')
  c=c*(i-j)//(j+1)
 print()
```

## Sample Output
<img width="358" height="677" alt="image" src="https://github.com/user-attachments/assets/a74aa10e-a6fe-4e24-bbdf-45978d23119c" />

## Result
Thus to write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user is implemented.

