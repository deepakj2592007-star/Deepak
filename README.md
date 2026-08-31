# Deepak
Python expense - tracker 
🧾 Expense Tracker (Python CLI)
A clean and lightweight Command-Line Expense Tracker built with Python. This tool helps you record, view, and analyze your daily spending — right from your terminal. All data is stored locally in a JSON file, making it simple, portable, and database-free.

📋 Table of Contents
- Overview
- Features
- Tech Stack
- Installation & Usage
- Project Structure
- Data Format
- Key Concepts Practiced
- Future Enhancements

🧠 Overview
This project is a CLI-based expense management tool that allows users to track everyday spending efficiently. It lets you:

- Add expenses with amount, category, and notes
- View all recorded expenses
- See category-wise spending summaries
- Delete unwanted entries

It’s a practical Python project demonstrating file handling, data persistence, and menu-driven CLI programming.

✨ Features
✅ Add Expense – Enter amount, category, and an optional note.
✅ View All Expenses – See every recorded transaction with date and description.
✅ Category Summary – Get total spending per category (e.g., Food ₹350, Travel ₹200).
✅ Delete Expense – Remove specific entries by their index.
✅ Persistent Data – All records are stored locally in expenses.json.

🧰 Tech Stack
| Component | Description |
|---|---|
| Language | Python 3 |
| Libraries Used | json, os, datetime (all standard Python libraries) |
| Storage | Local JSON file |

No external dependencies are required — it runs out of the box with any standard Python installation.

⚙️ Installation & Usage
1️⃣ Clone the Repository
git clone https://github.com/<YOUR-USERNAME>/expense-tracker.git
cd expense-tracker

2️⃣ Run the Program
Make sure you have Python 3 installed, then run:
python expense_tracker.py

3️⃣ Choose from the Menu
========== Expense Tracker ==========
1. Add expense
2. View all expenses
3. View summary by category
4. Delete an expense
5. Exit

🗂️ Project Structure
expense-tracker/
│
├── expense_tracker.py     # Main Python script
├── expenses.json          # Auto-created data file
└── README.md              # Project documentation

💾 Data Format
All expenses are stored in expenses.json as a list of dictionaries:

[
  {
    "amount": 150.0,
    "category": "Food",
    "note": "Lunch with friends",
    "date": "2026-08-30"
  },
  {
    "amount": 80.0,
    "category": "Travel",
    "note": "Metro ticket",
    "date": "2026-08-30"
  }
]

🧩 Key Concepts Practiced
This project helps strengthen core programming skills:

- Python Fundamentals: Variables, loops, conditionals, user input validation
- Modular Design: Breaking logic into reusable functions
- File I/O & JSON: Reading and writing structured persistent data (`json.load`, `json.dump`)
- Data Structures: Managing collections using lists and dictionaries
- Flow Control: Building interactive menu loops

🚀 Future Enhancements
- 🔍 Filter expenses by custom date ranges or monthly totals
- 📊 Export summary reports to CSV format
- 📈 Visualize spending patterns using Matplotlib/Seaborn
- 🖥️ Build a desktop GUI version with Tkinter or a web dashboard with Flask/Streamlit

🧑‍💻 Author
Deepak
AI & DS Student | Python Course Project
📍 India
💼 Main Theme: Track everyday spending efficiently.
