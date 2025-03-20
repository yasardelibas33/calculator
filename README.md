# Simple Calculator

## Description
This is a simple calculator application built using Java and Swing. The calculator supports basic arithmetic operations including addition, subtraction, multiplication, and division. It also includes functionalities such as decimal input, clearing input, deleting a character, and negating a number.

## Features
- **Addition (+)**
- **Subtraction (-)**
- **Multiplication (*)**
- **Division (/)**
- **Decimal point (.)**
- **Equals (=) to compute the result**
- **Delete (removes last digit)**
- **Clear (clears the input field)**
- **Negate (changes the sign of the number)**

## Technologies Used
- **Java**
- **Swing** (`JFrame`, `JPanel`, `JButton`, `JTextField`)
- **AWT** (`Font`, `GridLayout`, `ActionListener`)

## How to Run
1. Ensure you have **Java** installed on your system.
2. Copy the `Calculator.java` file into your preferred Java project directory.
3. Open a terminal or command prompt and navigate to the directory.
4. Compile the program using the following command:
   ```sh
   javac Calculator.java
   ```
5. Run the program using:
   ```sh
   java Calculator
   ```
6. The calculator GUI should open, allowing you to perform calculations.

## Code Overview
- The program creates a **GUI** using `JFrame`.
- `JTextField` is used to display input and results.
- `JButton` elements represent number keys and function buttons.
- `ActionListener` is implemented to handle button clicks and perform operations accordingly.
- The `actionPerformed` method manages user interactions.

## Future Enhancements
- Implement **parentheses support**.
- Add **keyboard input functionality**.
- Include **advanced mathematical operations** (e.g., square root, exponentiation).

