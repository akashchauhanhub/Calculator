# Calculator
This is a simple calculator built using Python's tkinter library for the graphical user interface (GUI). It allows the user to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator also supports handling floating-point numbers and displays results instantly after performing calculations.

## Features
- Supports basic arithmetic operations: addition (+), subtraction (-), multiplication (*), and division (/).
- Provides a clear button to reset the calculator's display.
- Handles floating-point numbers (decimals).
- Uses Python's eval() function to evaluate mathematical expressions.
- Displays results or error messages when invalid input is entered.
## Installation
- Make sure you have Python 3.x installed on your machine.
- The program uses the tkinter module, which is included by default with Python, so you don't need to install any additional packages.
## Running the Application
- Save the provided Python code into a file named calculator.py.

- Open a terminal or command prompt.

- Navigate to the directory where calculator.py is saved.

- Run the application by typing:

```
python calculator.py
```
- This will open a window with a simple calculator interface.

## GUI Layout
#### The calculator window consists of:

- Input/Display Area: A large entry widget at the top where the user can see the current expression or the result.
- Buttons:
       - Number buttons: 0-9 for input.
       - Decimal point button: . for floating-point numbers.
       - Operator buttons: +, -, *, / for arithmetic operations.
       - = button to evaluate the expression and show the result.
       - C button to clear the entry field.
## How to Use
- Click on number buttons (0-9) and the operator buttons (+, -, *, /) to create a mathematical expression.
- Click the = button to evaluate the expression and display the result in the entry widget.
- Use the C button to clear the entry field if you want to reset the calculator.
- If you enter an invalid expression, such as 2++2, the calculator will display Error.
## Example Usage
- Input: 3 + 5
     Output: 8

- Input: 12 / 4
     Output: 3.0

- Input: 5 * (2 + 3)
     Output: 25

- Input: 2 + + 3
     Output: Error (invalid syntax)

## Code Explanation
- The calculator uses the tkinter library to create a GUI window.
- The entry widget (entry) is used to display the current expression and results.
- There are buttons for digits, operators, and functions (clear and equals).
- The button_click(value) function updates the entry widget when a button is pressed.
- The evaluate_expression() function evaluates the expression in the entry widget and displays the result.
- The clear_entry() function clears the entry widget when the "C" button is pressed.





