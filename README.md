# personal-finance-management
# 💰 Personal Finance Management System

## 📌 Project Overview
The **Personal Finance Management System** is a Python-based application that helps users manage their personal finances by tracking income, expenses, and monthly budgets. It provides a dashboard to view financial details, monitor spending, and maintain transaction records.

The project uses SQLite to store financial data and provides an interactive interface using Python widgets.

## 🎯 Objectives
- Track income and expenses.
- Add and manage financial transactions.
- Set monthly budgets.
- Monitor monthly income, expenses, and balance.
- Check budget limits and receive alerts when expenses exceed the budget.
- View recent transaction records.
- Export transactions to an Excel file.

## 🛠️ Technologies Used
- **Python** – Main programming language
- **SQLite** – Database for storing transactions and budgets
- **Pandas** – Data handling and analysis
- **Matplotlib** – Data visualization
- **ipywidgets** – Interactive user interface
- **Openpyxl** – Excel file support

## ✨ Features

### 1. Income and Expense Tracking
Users can record income and expenses by entering the transaction type, amount, category, date, and description.

### 2. Monthly Dashboard
Displays:
- Total income
- Total expenses
- Remaining balance
- Monthly budget

### 3. Budget Management
Users can set a monthly budget and monitor their expenses.

### 4. Budget Alert
If expenses exceed the set budget, the application displays an alert showing the exceeded amount.

### 5. Transaction History
Displays the latest 15 transactions with details such as ID, type, amount, category, date, and description.

### 6. Delete Transactions
Users can delete transactions using their transaction ID.

### 7. Excel Export
All transaction records can be exported into an Excel file for further analysis.

## 📂 Database Structure

### Transactions Table

| Column | Description |
|---|---|
| id | Unique transaction ID |
| type | Income or Expense |
| amount | Transaction amount |
| category | Transaction category |
| description | Transaction description |
| date | Transaction date |





## 🔮 Future Enhancements
- Add category-wise expense charts.
- Add transaction search and filtering.
- Support multiple monthly budgets.
- Improve the dashboard design.
- Add a login system for user security.

## 📝 Conclusion
The Personal Finance Management System provides a simple and effective way to track income, expenses, and monthly budgets. It helps users understand their spending habits, maintain transaction records, and manage their money more efficiently. Through this project, I gained practical experience in Python, database management, data visualization, and building interactive applications.
