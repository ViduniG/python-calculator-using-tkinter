Feature

Basic arithmetic: addition, subtraction, multiplication, division
Decimal point support
Positive/negative toggle (+/-)
Percentage conversion (%)
Square root (√)
All Clear (AC) reset
Custom pastel color theme, styled to work correctly on macOS using ttk and the clam theme

How It Works
Numbers typed are stored in one of two variables (A for the first number, B for the second), depending on whether an operator has been selected yet.
Pressing an operator (+, -, ×, ÷) stores the chosen operation and switches input over to building the second number.
Pressing = converts both numbers to floats, performs the calculation based on the stored operator, and displays the result.
AC resets all stored values back to their starting state.


Built With
Python 3
Tkinter (ttk module, clam theme for cross-platform button styling)

(Note- This was my first project with Tkinter)


Author: Viduni.G
