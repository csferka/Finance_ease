Unified App: Expense Tracker & Stock Market Analyzer

This application provides two functionalities in one interface:

Expense Tracker: Allows users to input their expenses, view the total expenses, and analyze the distribution of expenses in a pie chart.
Stock Market Analyzer: Fetches stock data using the Alpha Vantage API, compares the daily stock price, and sends an email with relevant stock news if there's a significant price change.
Features

Expense Tracker:
Add expenses with item names, quantities, and cost per unit.
View a table of all recorded expenses.
Analyze the distribution of expenses with a pie chart.
Clear the inputs and clear the expense list.
Stock Market Analyzer:
Fetch daily stock data from Alpha Vantage API.
Compare the stock price of the previous two days and calculate the percentage change.
Fetch the latest news related to the stock from NewsAPI.
Send the analysis and stock news to a specified email address.
Prerequisites

Ensure you have the following installed:

Python 3.x
Required Python libraries:
tkinter (for GUI)
matplotlib (for generating charts)
requests (for API requests)
smtplib (for sending emails)
To install the required libraries, run:

pip install matplotlib requests
API Keys

You need to obtain API keys for the following services:

Alpha Vantage (for stock data)
Go to Alpha Vantage and sign up for an API key.
Set the STOCK_API_KEY variable in the code.
NewsAPI (for fetching stock-related news)
Go to NewsAPI and sign up for an API key.
Set the NEWS_API_KEY variable in the code.
SMTP Credentials (for sending emails)
If using Gmail, generate an App Password for your email account (in case you're using two-factor authentication).
Set the MY_EMAIL and PASSWORD variables in the code with your email and app password.
Usage

Clone the repository or download the script to your local machine.
Open the script and replace the placeholders for the API keys and email credentials.
Run the script using Python:
python <script_name>.py
The GUI window will open with the following tabs:

Expense Tracker: Input your expenses, view a table, and analyze expenses.
Stock Market Analyzer: Input stock names and your recipient email to receive stock analysis and news.
