#

Simple Python CLI Calculator
A lightweight, command-line interface (CLI) calculator built with Python. This tool performs fundamental arithmetic operations with built-in error handling for a smooth user experience.

Features
Standard Operations: Supports Addition, Subtraction, Multiplication, and Division.

Continuous Execution: Uses a logic loop to allow multiple calculations without restarting the script.

Input Validation: Handles non-numeric inputs gracefully to prevent crashes.

Safety Features: Includes specific checks to prevent "Division by Zero" errors.

Precision: Supports floating-point (decimal) numbers for accurate calculations.

Getting Started
Prerequisites
Python 3.x installed on your machine.

Installation
Clone this repository or download the source code.

Open VS Code, terminal, or command prompt.

Navigate to the directory containing the file:

Bash
cd path/to/your/calculator
Usage
Run the script using the Python interpreter:

Bash
python calculator.py
How it works:
Select Operation: Choose from the menu (1-4).

Enter Values: Provide the two numbers you wish to calculate.

View Result: The calculated value will be displayed immediately.

Continue or Exit: Choose to perform another calculation or close the program.

Project Structure
calculator.py: The main script containing the arithmetic logic and user interface.

README.md: Project documentation and setup guide.

Example
Plaintext
Select operation:
1.Add
2.Subtract
3.Multiply
4.Divide

Enter choice (1/2/3/4): 1
Enter first number: 10
Enter second number: 5
10.0 + 5.0 = 15.0
