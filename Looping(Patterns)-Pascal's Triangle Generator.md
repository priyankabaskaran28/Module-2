## 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## 🧠 Algorithm

Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.

## 🧪 Program

```
import math
def pascal_triangle(rows):
    for n in range(rows):
        print(" " * (rows - n), end="")

        for k in range(n + 1):
            value = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
            print(value, end=" ")

        print()

rows = int(input("Enter the number of rows: "))
pascal_triangle(rows)
```
## Sample Output:

<img width="663" height="550" alt="image" src="https://github.com/user-attachments/assets/eeb5bf27-ad9c-43cd-bdfd-357c112cca05" />

## Result:

Thus to write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is done successfully.
