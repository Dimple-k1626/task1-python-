:

🧮 Simple Python Calculator

A beginner-friendly command-line calculator built using Python.
This program performs Addition, Subtraction, Multiplication, and Division with proper input validation and error handling.

🚀 Features

✔️ User-friendly menu-based interface

✔️ Supports all basic arithmetic operations

✔️ Handles invalid inputs gracefully

✔️ Prevents division by zero

✔️ Runs until the user chooses to exit

📂 File Structure
calculator/
│
├── calculator.py   # Main calculator program
└── README.md       # Documentation

🛠️ How It Works

The program displays a menu with 5 options:

Addition

Subtraction

Multiplication

Division

Exit

The user selects an operation and then enters two numbers.
The program calls the respective function (add(), subtract(), multiply(), divide()) and prints the result.

📘 Functions Overview
Function	Description
add(a, b)	Returns the sum of two numbers
subtract(a, b)	Returns the difference
multiply(a, b)	Returns the product
divide(a, b)	Performs division and handles divide-by-zero
calculator()	Main loop displaying menu and collecting user inputs
▶️ How to Run the Program

Make sure Python is installed

Save the script as calculator.py

Open a terminal and run:

python calculator.py

📌 Example Output
---- Simple Calculator ----

Choose an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Exit
Enter your choice (1-5): 1
Enter first number: 10
Enter second number: 20
Result: 30.0

🛡️ Error Handling

Prevents dividing by zero

Ensures the choice is valid

Catches non-numeric inputs

📜 License

This project is free to use for learning and practice.
