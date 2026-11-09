Simple Calculator

Simple Calculator is a console-based C++ program that allows users to perform basic arithmetic operations on two numbers. It supports addition, subtraction, multiplication and division. It also handles division by zero and invalid operators.

Requirements

Item| Requirement
Operating System| Windows 10/11, Linux, or macOS
Language| C++
Compiler| g++ (GCC) or any compatible C++ compiler
Libraries| C++ Standard Library only ("iostream")

Installation

1. Clone the repository:
   "git clone <your-repository-link>"
2. Enter the project folder:
   "cd simple-calculator"
3. Compile the program:
   "g++ simplecalculator.cpp -o calculator"

To start it, run "./calculator" (Linux/macOS) or "calculator.exe" (Windows).

Minimal Working Example

Run the program, then type the following inputs in order:

===== SIMPLE CALCULATOR =====
Enter first number: 10
Enter an operator (+, -, *, /): +
Enter second number: 5

Expected output:

Result: 15

Features

- Addition of two numbers (+)
- Subtraction of two numbers (-)
- Multiplication of two numbers (*)
- Division of two numbers (/)
- Supports decimal numbers
- Checks division by zero
- Displays an error for invalid operators

Project Structure

Component| Purpose
"iostream"| Handles input and output operations
"main()"| Starting point of the program
"num1", "num2"| Store the two numbers entered by the user
"operation"| Stores the arithmetic operator
"switch" statement| Selects and performs the required arithmetic operation
"if-else" statement| Checks division by zero
"default" case| Handles invalid operators

Known Limitations

Performs calculations on only two numbers at a time.
Does not support advanced mathematical operations.
 Does not validate non-numeric user input.
The program exits after performing one calculation.

Project Information

Project Name: Simple Calculator
Language: C++
Project Type: Console-Based Application
