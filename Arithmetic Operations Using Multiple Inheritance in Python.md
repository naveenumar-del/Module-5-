Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates multiple inheritance by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

🎯 Aim

To write a Python program to calculate Add, Sub & Division using Multiple Inheritance.


🧠 Algorithm

Define Calculation1 class

Contains Summation(a, b) method to return the sum of two numbers.

Define Calculation2 class

Contains Subtraction(a, b) method to return the difference of two numbers.

Define Derived class

Inherits from both Calculation1 and Calculation2.


Contains Division(a, b) method to return the division result.

Input

Prompt the user to enter two numbers.

Process

Create an object of the Derived class.

Call Summation, Subtraction, and Division methods.

Output

Display the results of the three operations.

💻 Program

class Calculation1:

    def Summation(self, a, b):
        return a + b

class Calculation2:

    def Subtraction(self, a, b):
        return a - b

class Derived(Calculation1, Calculation2):

    def Division(self, a, b):
        if b != 0:
            return a / b
        else:
            return "Error: Division by zero"

a = int(input())
b = int(input())
obj = Derived()

print(obj.Summation(a, b))
print(obj.Subtraction(a, b))
print(obj.Division(a, b))

Output Example

<img width="1259" height="246" alt="image" src="https://github.com/user-attachments/assets/ae489232-ba76-4ca6-831c-0e06538344f6" />


Result

Thus the program demonstrates multiple inheritance by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes has been executed successfully.
