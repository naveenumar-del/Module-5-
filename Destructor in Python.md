Destructor in Python

This project demonstrates how to implement a destructor in Python using a simple class.


🚀 Overview

The program defines a class Demo with:


A constructor __init__ that initializes an instance variable and prints a message.

A destructor __del__ that prints a message when the object is destroyed.

🧠 Algorithm

Define a class named Demo.

Inside the class, define the __init__ method:

Initialize an instance variable status with the value "Alive".

Print the value of status.

Define the __del__ method:

Print a message indicating the object is being destroyed.

Outside the class:

Create an instance of the Demo class.

Delete the object using the del keyword.

Program

class Demo:

    def __init__(self):
        print("Hello World!")

    def __del__(self):
        print("Hello from the __del__ method.")

# Create and delete the object
obj = Demo()
del obj

🧪 Output

<img width="1254" height="215" alt="image" src="https://github.com/user-attachments/assets/3c9b995a-bd77-4f49-ae60-56bbb04bc77d" />


Result

Thus the program demonstrates how to implement a destructor in Python using a simple class has been executed successfully.
