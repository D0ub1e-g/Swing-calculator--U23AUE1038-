Swing Calculator

OVERVIEW

Swing Calculator is a simple GUI-based calculator built using Java Swing. It allows users to perform basic arithmetic operations, including addition, subtraction, multiplication, and division. The interface consists of a text field to display input and results, along with buttons for digits (0-9), operators (+, -, *, /), a clear (C) button, and an equals (=) button.

FEATURES

Supports four basic arithmetic operations: addition, subtraction, multiplication, and division.

A clear (C) button to reset the calculator.

A responsive GUI built using Java Swing with GridLayout for button arrangement.

Displays results in real-time upon pressing the "=" button.


PREREQUISITES

Ensure you have the following installed:

Java Development Kit (JDK) 8 or higher

An IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code)


How To Run

1. Clone or download the source code.


2. Open a terminal or command prompt in the project directory.


3. Compile the Java file:

javac SwingCalculator.java


4. Run the application:

java SwingCalculator



CODE EXPLANATION

The SwingCalculator class extends JFrame and implements ActionListener.

The GUI consists of a JTextField for displaying input/output and a panel (JPanel) containing buttons.

Buttons are added to a grid layout (4x4) with an event listener (actionPerformed).

Operators and numbers are processed accordingly when clicked.

The "=" button computes the result, while the "C" button resets the calculator.


FUTURE ENHANCEMENTS

Implement keyboard input support.

Add a decimal point (.) button for floating-point calculations.

Display an error message for division by zero instead of returning 0.


LICENSE

This project is open-source and available for modification and distribution.

AUTHOR
GABRIEL YASHIM GREGORY 








![1000011040](https://github.com/user-attachments/assets/40142b5f-04a6-49c8-933b-9793cc4264d7)
