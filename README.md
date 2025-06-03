## Assignment 6: GUI Calculator Using Tkinter
Develop a Python application that:

Presents a graphical interface for input and output.

Allows users to perform:

Addition

Subtraction

Multiplication

Division

Accepts input via clickable buttons (no keyboard input required).

Displays real-time results and clears input when requested.

Solution

Entry Widget

Displays numbers and results.

Acts as the calculator’s screen.

Buttons

Digits (0–9): Used for numeric input.

Operators (+, −, ×, ÷): Trigger arithmetic operations.

Equal (=): Executes the operation and displays the result.

Clear (C): Clears the screen for a new calculation.

## Functional Workflow
Number Input

Each digit button appends its value to the screen.

Operation Selection

When an operator button is clicked:

The current number is stored as the first operand.

The selected operation is remembered.

The input field is cleared for the next number.

Execution

On pressing =, the program:

Retrieves the second operand.

Performs the stored operation.

Displays the result in the input field.

Reset

Clicking clears the display and resets stored values.
