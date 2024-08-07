Classes
Expense: Represents an individual expense with attributes like description, amount, category, and date.

to_dict(): Converts the Expense object to a dictionary for JSON serialization.
from_dict(data): Creates an Expense object from a dictionary.
ExpenseTracker: Manages a list of expenses, handles file operations, and provides methods to add expenses and generate summaries.

load_expenses(): Loads expenses from a JSON file.
save_expenses(): Saves expenses to a JSON file.
add_expense(description, amount, category): Adds a new expense.
total_expenses(): Calculates the total amount spent.
monthly_summary(): Generates a summary of expenses by month.
category_summary(): Generates a summary of expenses by category.
display_expenses(): Displays all recorded expenses.
Example
plaintext
Copy code
Expense Tracker Menu
1. Add Expense
2. View Total Expenses
3. View Monthly Summary
4. View Category Summary
5. Display All Expenses
6. Exit
Contributing
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

