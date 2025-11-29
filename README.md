# Basic Calculator made with Python's Tkinter 🧮

A simple user-friendly desktop calculator built with Python's Tkinter library.  
Easily perform addition, subtraction, multiplication, and division with a clean, modern GUI.  
Created by **Srivarshini**.

## Features

- User-friendly graphical interface
- Supports basic arithmetic operations: `+`, `-`, `*`, `/`
- Input field for expressions (e.g., `5+3`, `12/4`)
- Shows answers with rounding options for division
- Error handling for division by zero and invalid formats
- Welcome screen and animated transitions

## Getting Started

### Prerequisites

- Python (version 3.x recommended)
- Tkinter (usually included with Python)

### Running the Calculator

1. Download or clone this repository:
   ```sh
   git clone https://github.com/sri-is-coding/basic-calculator-tkinter.git
   ```
2. Open the **calculator.ipynb** notebook file in Jupyter Notebook or Jupyter Lab.
3. Run all the cells to start the calculator GUI.

> If you prefer, you can copy the code to a `calculator.py` file and run it directly:
> ```sh
> python calculator.py
> ```

## Usage

- Enter your calculation in the input field (for example: `8+4`, `15/3`).
- Click on numbers and operators, or type directly.
- Press `=` to compute the result.
- Use `Clear` to delete the input and output.
- Go back to the welcome screen using the `Back` button.

## Screenshots
<img width="245" height="287" alt="image" src="https://github.com/user-attachments/assets/43e445e6-a3e4-4b6c-8e57-224f3ebc8bc1" />

## Screenshots

![Calculator Main Screen](images/calculator-main.png)

![Example Calculation](images/calculator-example.png)

## Error & Invalid Input Handling

Certain calculations or inputs may result in errors or warnings:

### **Errors**
- **Division by Zero:**  
  Entering a calculation like `5/0` will show an error popup (`Error: You cannot divide by zero!`).

- **Invalid Number Format:**  
  Inputs that aren't valid numbers, like `a+b` or `2+three`, will show an error (`Error: Invalid number format!`).

### **Invalid Inputs**
- **Missing Operator or Operand:**  
  Inputs like `123` or `+123` or `7+` are not valid expressions—the calculator will prompt:  
  *"Not possible, I received invalid input!"*

- **Multiple Operators:**  
  Expressions like `2+3+4` (more than one operator) are not supported.

- **Unsupported Characters:**  
  Special characters or inputs that don't match the format `number operator number` (e.g. `5&2`) are considered invalid.

---

**Made with ❤ by Srivarshini**
