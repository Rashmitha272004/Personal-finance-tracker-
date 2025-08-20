# Personal-finance-tracker-
This is a simple personal finance tracker application built with Python. It allows users to track their income and expenses, manage budgets, receive alerts, view transactions, and generate detailed financial reports.

Features
1. Add Income and Expense Transactions: Easily add and categorize your income and expenses.
2. View Transactions: View a detailed list of all your transactions, including dates, categories, and descriptions.
3. Budget Management: Set budgets for different categories and monitor your spending against these budgets.
4. Alerts and Notifications: Receive real-time alerts via AWS SNS when your spending exceeds or approaches your budget limits.
5. Financial Reports: Generate comprehensive financial reports and export them to CSV for further analysis.
6. SQLite Database: Securely store all financial data using SQLite.

Installation
1.	Fork the Repository:
Click the Fork button at the top right corner to create a copy of the repository in your GitHub account.
2.	Clone Your Forked Repository:
Replace your-username with your GitHub username in the following command:
git clone https://github.com/your-username/personal-finance-tracker.git
3.	Navigate to the Project Directory:
cd personal-finance-tracker
4.	Install the required dependencies:
pip install -r requirements.txt

Usage
1 Run the main script to start the application: 

python main.py
Follow the on-screen prompts to add transactions, view transactions, and generate reports.

Project Structure

1•	main.py: The main script that runs the application.

2•	database.py: Handles database operations.

3•	transaction.py: Defines the Transaction class.

4•	report.py: Contains functions for generating financial reports.

5•	config.py: Stores configuration settings.

6•	requirements.txt: Lists the project dependencies.

7•	README.md: This file, containing project information and instructions.

