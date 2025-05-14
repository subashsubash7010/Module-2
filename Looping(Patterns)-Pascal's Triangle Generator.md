# Ex2(d) 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
Developed By: V Mythili
Reg No: 212223040123

```
rows = int(input())
x = 1
for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            x = 1
        else:
            x *= (i - j)//j
               print(x, end = " ")
    print()
```


## Output


![image](https://github.com/user-attachments/assets/8d61b54b-1e50-4d1a-97d7-5a24e1b99620)

## Result

Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.**
