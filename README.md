Akshaya Sree G
212225230011
# 1.Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=16
print(bin(a))
```

## Output
<img width="601" height="575" alt="image" src="https://github.com/user-attachments/assets/98b45629-aca2-45eb-8d37-796e47d1b899" />

## Result
Thus to write a Python program to convert the number **16** into its **binary representation** using built-in Python functions is implemented.

# 2. Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a,b):
 print(a%b)
a=int(input())
b=int(input())
result(a,b)
```
## Output
<img width="601" height="575" alt="image" src="https://github.com/user-attachments/assets/04b95f13-f1ab-49f0-8d2c-46936a7f88d6" />

## Result
Thus to write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator is implemented.

# 3.Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))
```
## Output
<img width="400" height="622" alt="image" src="https://github.com/user-attachments/assets/a2c07bec-abeb-4f24-b548-cd9d8b771aea" />

## Result
Thus to write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum is implemented.

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

## 5.Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
temp=num
rev=0
while temp>0:
 rev=(10*rev)+temp%10
 temp=temp//10
if rev==num:
 print("Palindrome")
else:
 print("Not Palindrome")
```
## Output
<img width="348" height="686" alt="image" src="https://github.com/user-attachments/assets/984d26c5-9c97-4182-bf13-94fc2d6e48cf" />

## Result
Thus to write a Python program that checks whether a given number is a **palindrome** using loops is implemented.
