# CODSOFT
NAME: JENIFER Y
DOMAIN : PYTHON PROGRAMMING
TASK 1 : SIMPLE CALCULATOR
INTRODUCTION:
   ->This program is a Simple Calculator application created using Python's Tkinter library, designed to perform basic arithmetic operations in an intuitive, user-friendly interface. This calculator includes all essential features: buttons for digits and arithmetic operators, a display for entering and viewing expressions, and functionality to calculate, clear, and handle errors gracefully.
   ->Tkinter provides a way to create graphical elements like buttons and text fields, making it ideal for building desktop applications in Python. With this calculator, users can perform operations like addition, subtraction, multiplication, and division in real time, similar to a standard calculator, but with the added benefit of being a lightweight, customizable Python-based tool.
  ->This calculator demonstrates essential GUI programming concepts, such as event handling, layout management, and styling. Here’s a breakdown of the technologies and components involved in building this project.
  
Tkinter Library:
Overview: Tkinter is Python's standard library for creating graphical user interfaces (GUIs). It provides tools to build windows, buttons, text fields, and other elements that users interact with.
Elements in this program: tk.Tk(), tk.Button, and tk.Entry are core widgets of Tkinter used here to create the main window, buttons for each digit/operator, and an entry widget for displaying calculations.

2. Event Handling with Button Clicks
Button Actions: Each button, when clicked, triggers a specific function. For example, pressing a number button calls on_button_click(value), which appends the button's value to the display.
Lambda Functions: lambda val=text: on_button_click(val) is used here to dynamically pass the text of each button to on_button_click. This makes each button uniquely responsive to its own input.

4. Functions
on_button_click(value): Handles the input of digits and operators, updating the display with each click.
calculate(): Called when the "=" button is pressed. The eval() function in Python is used here to evaluate the string as a mathematical expression.
clear(): Clears the display when the "C" button is pressed.

6. Grid Layout System
Tkinter’s grid() method is used here for layout management, which organizes the calculator's buttons into a 4x4 grid, placing each button in a specific row and column on the grid. This layout system makes it easier to control the position of each widget.

8. Styling and Colors
Background and Text Color: Color codes are used to style buttons, background, and text. For instance, #2e2e2e for the background, and specific colors for number, operator, equal, and clear buttons. These colors are applied to create a modern look and enhance user experience.
Font and Button Size: Font and button size specifications like ("Arial", 18) make the buttons and display more readable.

10. Tkinter Main Loop
The root.mainloop() function starts the Tkinter event loop, keeping the application window open and responsive to user interactions until it is closed.
-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x
How It Works Together
When the application starts, Tkinter displays the main window with a grid of buttons and an entry display.
Each button click updates the display or performs a calculation, with the result shown in real-time.
Styling and layout make the application visually appealing and intuitive for users.
This simple but effective setup allows users to perform basic calculations in a user-friendly graphical environment using Python's GUI toolkit.






