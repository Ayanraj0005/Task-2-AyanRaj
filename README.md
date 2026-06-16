# 💰 Expense Tracker

A simple command-line Expense Tracker built with Python that allows users to record expenses one at a time and continuously calculate a running total. The program provides real-time updates and displays the final total when the user exits.

---

## 🚀 Features

- Add expense amounts continuously
- Real-time running total calculation
- Input validation using exception handling
- Simple and interactive command-line interface
- Final expense summary on exit
- Beginner-friendly Python project

---

## 📂 Project Structure

```
Expense_Tracker/
│
├── expense_tracker.py    # Main application
└── README.md            # Project documentation
```

---

## 🛠️ Technologies Used

- Python 3
- Functions
- Loops
- Exception Handling
- User Input Processing

---

## ⚙️ How It Works

### Step 1: Start the Application

When the program starts, the expense tracker menu is displayed:

```text
--- Expense Tracker ---
Type 'quit' to exit and see your final total.

Enter your expense amounts one by one.
```

---

### Step 2: Enter Expenses

Users can enter expense amounts one at a time.

Example:

```text
Enter expense amount: 150
Added! Current running total: $ 150.0

Enter expense amount: 200
Added! Current running total: $ 350.0

Enter expense amount: 300
Added! Current running total: $ 650.0
```

Each valid amount is automatically added to the running total.

---

### Step 3: Handle Invalid Inputs

If a user enters something other than a number, the program displays an error message:

```text
Enter expense amount: abc

Invalid Data. Please enter a valid number.
```

This prevents the application from crashing.

---

### Step 4: Exit the Program

Type:

```text
quit
```

to stop entering expenses and view the final total.

Example:

```text
Enter expense amount: quit
```

---

## 📊 Sample Output

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

Enter expense amount: 450
Added! Current running total: $ 1100.0

Enter expense amount: 500
Added! Current running total: $ 1600.0

Enter expense amount: quit

==============================
FINAL TOTAL: $ 1600.0
==============================
```

---

## 🧩 Code Structure

### Global Variable

```python
total = 0.0
```

Stores the accumulated expense total.

---

### `tracker()`

Responsible for:

- Accepting user input
- Converting input to numbers
- Updating the running total
- Handling invalid inputs
- Exiting when the user types `quit`

---

### `menu()`

Displays instructions and starts the expense tracking process.

---

## ▶️ Running the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/expense-tracker.git
```

### Navigate to the Project Folder

```bash
cd expense-tracker
```

### Run the Program

```bash
python3 expense_tracker.py
```

---

## 📚 Python Concepts Demonstrated

- Variables
- Functions
- While Loops
- Conditional Statements
- Type Conversion
- Exception Handling (`try-except`)
- User Input Processing

---

## 🔮 Future Improvements

- Store expenses in a file
- Categorize expenses (Food, Travel, Shopping, etc.)
- Daily/Monthly expense reports
- Expense history viewing
- Data visualization using Matplotlib
- Export reports to CSV
- Budget tracking and alerts

---

## 🎯 Learning Objectives

This project helps beginners understand:

- Continuous input processing
- Running calculations
- Error handling
- Function-based program design
- Building practical CLI applications

---

## 👨‍💻 Author

**Raj Ayan**

Built as a Python learning project to practice loops, functions, user input handling, and expense management through a command-line application.
