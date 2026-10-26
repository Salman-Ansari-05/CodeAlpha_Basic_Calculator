# Simple Calculator in C

A simple menu-driven calculator written in C that performs basic arithmetic operations on two numbers: addition, subtraction, multiplication, and division.

## Features

- **Addition (+):** Adds two numbers.
- **Subtraction (-):** Subtracts the second number from the first.
- **Multiplication (*):** Multiplies two numbers.
- **Division (/):** Divides the first number by the second.
- **Division by Zero Handling:** Prevents division by zero and displays an error message.
- **Input-Based Menu:** Allows users to select an operation from a menu.
- **Formatted Output:** Displays results up to two decimal places.

## Technologies Used

- C Programming Language
- Standard Input/Output Library (`stdio.h`)
- `switch-case` statements
- Variables and data types (`int`, `float`)
- Conditional statements (`if-else`)

## Requirements

- A C compiler, such as GCC
- A terminal or command prompt

## How to Run

### 1. Save the Source Code

Save the program in a file named `main.c`.

### 2. Compile the Program

Using GCC, run:

```bash
gcc main.c -o main
```

### 3. Execute the Program

On Linux or macOS:

```bash
./main
```

On Windows:

```bash
main.exe
```

## Usage

1. Enter the first number.
2. Enter the second number.
3. Select an arithmetic operation by entering a number from 1 to 4:
   - `1` - Addition
   - `2` - Subtraction
   - `3` - Multiplication
   - `4` - Division
4. View the calculated result.

## Example

### Input

```text
Enter first number: 10
Enter second number: 5

Select an operation:
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
Enter your choice (1-4): 1
```

### Output

```text
Result = 15.00
```

## Error Handling

- **Division by Zero:** If the second number is zero and division is selected, the program displays an error message instead of performing the division.
- **Invalid Choice:** If the user selects an option outside the range 1–4, the program displays an invalid choice message.

## Limitations

- Performs only one operation per execution.
- Accepts two numbers at a time.
- Uses floating-point numbers (`float`) for calculations.
- Assumes the user enters valid numeric input.

## Future Improvements

- Allow multiple calculations without restarting the program.
- Add support for modulus, exponentiation, and other mathematical operations.
- Improve input validation.
- Provide an option to exit through the menu.

## License

This project is available for educational and personal use. You may modify and extend it as needed.

## Author

SALMAN ANSARI

Created as a beginner-friendly C programming project to demonstrate basic arithmetic operations, conditional statements, and switch-case control flow.
