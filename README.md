# 💬 Natural Language Processing-Based Personal Expense Tracker

A lightweight Python console application that parses free-text expense sentences (e.g., *"bought coffee for 200"*, *"spent 150 on a cab"*), extracts the amount and category using regular expressions (Regex), and stores them in a relational SQLite database.

## 🚀 Key Features

- **Natural Language Text Parsing:** Automatically extracts numerical amounts and spending categories from free-form user sentences using Python's `re` module.
- **Relational Database Management:** Securely stores and manages records using SQLite3.
- **SQL Analytics:** Generates dynamic group summaries using SQL `GROUP BY` and aggregate functions (`SUM`).
- **Data Visualization:** Plots category-based expense distributions using `Matplotlib` (Pie Chart).

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Database:** SQLite3
- **Data Analysis & Viz:** Pandas, Matplotlib
- **Text Processing:** Regular Expressions (`re`)

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/nlp-expense-tracker.git](https://github.com/KULLANICI_ADIN/nlp-expense-tracker.git)
   cd nlp-expense-tracker
