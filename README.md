# Expense-Tracker-using-Python

This is a Python-based expense tracker application that helps you record, categorize, and analyze your expenses. It provides a simple way to monitor your spending habits and calculate your daily budget based on your remaining funds and days left in the month.

## Features

- **Record Expenses**: Add expenses with details like name, amount, and category.
- **Expense Categories**: Categorize expenses under predefined categories: `Food`, `Travel`, `Fun`, `Work`, `Misc`.
- **File Storage**: Save all recorded expenses in a CSV file for future reference.
- **Expense Summary**: View total spending by category, remaining budget, and suggested daily budget for the rest of the month.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/expense-tracker.git
   cd expense-tracker
   ```

2. Ensure you have Python 3 installed. You can check your Python version using:
   ```bash
   python --version
   ```

3. Install any required dependencies (if applicable). Currently, this script doesn't require external libraries.

## Usage

1. Run the program:
   ```bash
   python main.py
   ```

2. Follow the prompts:
   - Input the name of the expense.
   - Enter the amount spent.
   - Select the category from the predefined list.

3. The application will:
   - Save the expense to `expenses.csv`.
   - Provide a summary of your spending, including category-wise totals, remaining budget, and daily budget.

## Project Structure

```
expense-tracker/
├── main.py          # Main script to run the application
├── ex.py            # Contains the `expense` class definition
├── expenses.csv     # File where expenses are stored (auto-generated)
└── README.md        # Project documentation
```

## Example

```plaintext
$ python main.py
run ho raha h ky check kar rahe h!!!
ky kharcha karne wale h?
where do you spend the money: Groceries
kitna kharcha kiya h?: 500
Konse category me kharcha kar rahe ho?
1. Food
2. Travel
3. Fun
4. Work
5. Misc
category bata do: [1 - 5]: 1
Food
Kharcha file me save kar rahe h!!!
Hum summary bana rahe h!!
Groceries 500.0 Food
ye apka category wise kharcha h
Food: Rs.500.00
Itna kharcha hua h: Rs.500.0
Itne paise bake h: Rs.149500.0
Budget per day: Rs.4820.97
```

## Contributing

Feel free to contribute to this project! Create an issue or submit a pull request if you have suggestions for improvements or new features.


