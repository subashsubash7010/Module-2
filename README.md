# Ex2(a) Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
Developed By: Subash   M
Reg No: 212224220109
```
x=16
y=bin(x)
print(y)
```
## Output

![image](https://github.com/user-attachments/assets/61c66fe8-70ba-4fb1-978b-c159a48eac8f)


## Result

Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

# Ex2(b) Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
Developed By: Subash M
Reg No: 212224220109

```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```


## Output

![image](https://github.com/user-attachments/assets/634dffee-accb-481f-9de6-b88142dd39c8)


## Result

Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.


# Ex2(c) Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
Developed By: Subash M
Reg No: 212224220109

```
x=int(input())
y=int(input())
z=int(input())
f = lambda a, b,c: a+b+c
print(f(x,y,z))
```

## Output

![image](https://github.com/user-attachments/assets/5992a97b-fb85-4bb4-8b7b-02a66aeffb39)

## Result

Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

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
Developed By: Subash M
Reg No: 212224220109

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

Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

# Ex:2(e) Loops in Python: Palindrome Number Checker

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
Developed By: Subash M
Reg No: 212224220109


```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))
```
## Output

![image](https://github.com/user-attachments/assets/db577adc-b65e-4146-aa75-9a290519a65b)

## Result

Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
