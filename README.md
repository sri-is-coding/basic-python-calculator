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
<img width="200" height="300" alt="calculatormain" src="https://github.com/user-attachments/assets/ee25e8ae-a0bf-48ba-a723-ca03ae832566" />
<img width="200" height="300" alt="calculator" src="https://github.com/user-attachments/assets/33729ba6-c550-4674-b4b8-85a5e69d9f56" />
<img width="604" height="795" alt="examplecalculation" src="https://github.com/user-attachments/assets/4f048033-3b4a-491d-aea8-8fa5e1c1107f" />
<img width="606" height="800" alt="errorhandling" src="https://github.com/user-attachments/assets/21af0eb1-7b60-47be-a001-d244e1dfc79f" />
<img width="602" height="805" alt="invalidinput" src="https://github.com/user-attachments/assets/8d92866a-1537-4ea4-b7a4-26f45520051d" />
<img width="603" height="800" alt="image" src="https://github.com/user-attachments/assets/0e225319-e7ab-432f-8796-ea72e8ce4539" />

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
