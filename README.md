Scientific Calculator with GUI

A Python-based Scientific Calculator application built using the Tkinter library. This project provides a user-friendly graphical interface for performing basic arithmetic and advanced mathematical operations.


---

Features

1. Basic Arithmetic Operations:

Addition (+), Subtraction (-), Multiplication (*), and Division (/).



2. Advanced Mathematical Functions:

Square Root (√): Calculates the square root of a number.

Power (^): Computes exponential values.

Logarithms:

log: Base-10 logarithm.

ln: Natural logarithm (base e).


Trigonometric Functions:

sin, cos, tan: Compute trigonometric values for angles (input in degrees).


Factorial (!): Computes the factorial of a non-negative integer.



3. Error Handling:

Displays meaningful error messages for invalid operations (e.g., division by zero, invalid inputs).

Prevents application crashes using exception handling.



4. Interactive GUI:

Responsive buttons for input and operations.

Clean, keyboard-like layout for a familiar user experience.



5. Cross-Platform:

Runs on any system with Python and Tkinter installed.





---

Screenshots


(Replace this placeholder with actual screenshots of the application.)


---

How to Install and Run

Prerequisites

1. Python 3.x installed on your system.


2. Tkinter (pre-installed with Python on most distributions).



Steps to Run the Calculator

1. Clone the repository:

git clone https://github.com/your-username/scientific-calculator.git
cd scientific-calculator


2. Run the script:

python scientific_calculator_gui.py


3. A window will open displaying the scientific calculator.




---

Code Overview

The project is implemented using Python and structured as follows:

Class-Based Design: Encapsulates functionality in the ScientificCalculator class.

Key Methods:

create_widgets: Defines the GUI layout.

on_button_click: Handles button press events and performs operations.




---

Usage

Input: Enter numbers and operations via the buttons.

Output: Results are displayed in the entry field.

Clear: Use the C button to reset the input field.



---

Example Calculations


---

Error Handling

Division by Zero: Displays an error message.

Invalid Input: Shows a pop-up with the error details.



---

Future Enhancements

1. Enhanced Styling:

Use modern libraries like CustomTkinter for better aesthetics.



2. Expression Validation:

Replace eval() with a safer custom parser.



3. History Panel:

Add a feature to store and display calculation history.



4. Keyboard Input:

Allow users to interact with the calculator using a physical keyboard.





---

Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request with improvements.


---

License

This project is licensed under the MIT License.


---

Acknowledgements

Python Official Documentation: https://docs.python.org

.


