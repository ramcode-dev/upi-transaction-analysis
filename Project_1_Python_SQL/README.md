# UPI Transaction Analysis

A quick exploratory analysis project where I looked into UPI payment patterns, monthly spending trends, and ticket sizes using Python and SQLite.

## What I Did
1. **Cleaned the Data:** Handled missing values, stripped whitespace from column headers, and filtered for successful transactions.
2. **Ran In-Memory SQL:** Loaded the cleaned data into an in-memory SQLite database to run quick SQL queries directly in Python.
3. **Analyzed Trends:** Tracked how transaction volumes and average ticket sizes changed month-over-month (e.g., comparing June and July 2024 metrics across ₹25L+ total transaction value).

## Tools Used
* **Python 3** (Pandas)
* **SQLite3**
* **Google Colab**

## How to Run
1. Keep `upi_data.csv` in the same directory.
2. Open `upi_transaction_analysis.ipynb` in Colab or Jupyter and run the cells.
