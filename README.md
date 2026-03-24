Constructors in Python: Welcome Message with Student Name
🎯 Aim
To write a Python program that creates a Student class with a default constructor and a method to display a welcome message along with the student’s name provided by the user.

🧠 Algorithm
Get user input: Accept the student's name from the user.
Define the class: Create a class Student with a default constructor (__init__).
Default Constructor: In the constructor, assign the user input (student name) to an instance variable self.a.
Display Message: Define a method show that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
Execute the Program: Instantiate the Student class and call the show method.
🧾 Program
class Student:
    def _init_(self,a):
        self.a=a
    def get(self):
        self.a=input()
    def info(self):
        print("This is non parametrized constructor")
        print("Hello",self.a)
obj=Student()
obj.get()
obj.info()
Output
image
Result
Thus the program demonstrates how to implement a destructor in Python using a simple class has been executed successfully.
