Assignment 1
Module 2 - Basic Python Concepts
Task 1 : Perform Basic Mathematical Operations – 
In this task, two numbers are accepted from the user as input using the input () function. After accepting input, the values are type casted to float. Then the basic mathematical operations i.e. addition, subtraction, multiplication and division are performed on these values and result of each operation is displayed.
Code -
# 1st program of 1st Assignment. Demonstrating a basic calculator.

num1 = float(input("Enter first number : "))      #reading first number
num2 = float(input("Enter second number : "))     #reading second number

print()
print("Addition :", num1 + num2)                  # performing addition and printing result
print("Subtraction :", num1 - num2)
print("Multiplication:", num1 * num2)
print("Division:", num1 / num2)

#end of program.
Output -
 






Task 2 : Create a Personalised Greeting –
In this task, first name and last name of the user is accepted as input. Then first name and last name are concatenated to obtain the full name. After concatenation a personalized greeting message using the full name is printed on screen.

Code –
#2nd program of 1st Assigment. Demonstrating greeting message.

first_name = input("Enter your first name: ")  			 #input of first name
last_name = input("Enter your last name: ")     			#input of last name

full_name = first_name + " " + last_name
print("Hello,",full_name+"! Welcome to the Python program.")

#end of program

Output -
 
****************************
# TDPython_Assign1
