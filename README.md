Expense Categorizer and Tracker

Project Overview

The Expense Categorizer and Tracker is a Python-based application designed to help users record, organise, monitor, and manage their personal expenses.

The application automatically categorises expenses using keyword matching, calculates spending totals, tracks monthly budgets, and stores financial records for future use.

It was developed to demonstrate practical Python programming skills through the creation of a functional, real-world expense management solution.

Features

- Expense Recording: Add expenses with descriptions, amounts, categories, and dates.
- Automatic Categorisation: Automatically assigns categories based on keywords in expense descriptions.
- Expense Validation: Validates user inputs to prevent invalid records.
- Expense Management: View, edit, and delete recorded expenses.
- Spending Analysis: Calculate total spending, category-based spending, and monthly expenses.
- Monthly Budget Tracking: Set monthly budgets and monitor remaining balances.
- Budget Alerts: Receive notifications when spending approaches or exceeds the set budget.
- Search and Filtering: Search expenses by description and filter records by category.
- CSV Export: Export expense records into CSV format.
- Data Persistence: Save and retrieve financial records using JSON files stored in Google Drive.

Technologies Used

- Python
- Google Colab
- JSON
- CSV
- Google Drive
- Python Standard Libraries:
  - "datetime"
  - "json"
  - "csv"
  - "os"
  - "math"

Project Structure

The notebook is organised into nine main sections:

1. Expense Setup and Categorisation
2. Expense Recording and Validation
3. Viewing Recorded Expenses
4. Spending Calculations
5. Editing and Deleting Expenses
6. Searching and Filtering Expenses
7. Exporting Expense Records
8. Data Persistence and Storage
9. Application Startup and Data Initialisation

Data Storage

The application uses JSON files to preserve expense records and monthly budgets.

- "expenses.json" – Stores recorded expenses.
- "budgets.json" – Stores monthly budget information.
- "expenses.csv" – Contains exported expense records.

Data is stored in Google Drive to ensure records remain available between sessions.

How to Run

1. Open the project notebook in Google Colab.
2. Run the notebook sections in their intended order.
3. Authorise Google Drive access when prompted.
4. Use the available functions to record, manage, search, and analyse expenses.
5. Run "export_expenses()" to export expense records into CSV format.

Learning Outcomes

This project demonstrates practical experience with:

- Python functions and data structures.
- Conditional statements and loops.
- Input validation and error handling.
- File handling and data persistence.
- JSON and CSV data management.
- Problem-solving and application development.
- Building a functional solution to a real-world problem.

Project Status

Completed

The application includes functional expense management, automatic categorisation, budget tracking, data persistence, and CSV export capabilities.

Future Improvements

Potential improvements include:

- Developing a graphical user interface.
- Adding visual spending charts and reports.
- Introducing multiple user accounts.
- Generating automated monthly financial reports.