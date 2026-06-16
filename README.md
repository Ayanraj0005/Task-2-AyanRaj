# Expense Tracker

A simple command-line Expense Tracker built with Python. This application allows users to enter expense amounts one at a time, maintains a running total, and displays the final total when the user exits the program.

## Features

- Add expenses continuously
- Display a running total after each entry
- Input validation for non-numeric values
- View final total upon exit
- Simple and beginner-friendly Python implementation

## Requirements

- Python 3.x

## How to Run

1. Save the file as `expense_tracker.py`
2. Open a terminal and navigate to the project directory.
3. Run the program:

```bash
python expense_tracker.py
```

## Usage

Enter expense amounts one by one.

Example:

```text
--- Expense Tracker ---
Type 'quit' to exit and see your final total.

Enter your expense amounts one by one.

Enter expense amount: 150
Added! Current running total: $ 150.0

Enter expense amount: 200
Added! Current running total: $ 350.0

Enter expense amount: 300
Added! Current running total: $ 650.0

Enter expense amount: quit

==============================
FINAL TOTAL: $ 650.0
==============================
```

## Project Structure

```text
expense_tracker.py
```

### Main Components

#### Initialization

```python
total = 0.0
```

Stores the cumulative expense amount.

#### Tracker Function

```python
tracker()
```

- Accepts user input continuously.
- Converts valid input to a floating-point number.
- Updates the running total.
- Handles invalid entries using exception handling.

#### Menu Function

```python
menu()
```

- Displays instructions to the user.
- Starts the expense tracking process.

#### Final Output

Displays the total expenses after the user types `quit`.

## Error Handling

If a user enters invalid data:

```text
Enter expense amount: abc
Invalid Data. Please enter a valid number.
```

The program continues running until a valid amount or `quit` is entered.

## Future Improvements

- Store expenses in a list
- Display expense history
- Categorize expenses
- Save data to a file (CSV/JSON)
- Generate expense reports
- Add monthly and yearly summaries
- Create a graphical user interface (GUI)

## Learning Concepts Demonstrated

- Variables
- Functions
- Loops (`while`)
- Exception Handling (`try-except`)
- User Input
- Global Variables
- String Methods
- Basic Program Flow Control

## Author

Created as a beginner Python project for learning and practicing programming fundamentals.
