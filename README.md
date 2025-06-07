# 💰 Expense Tracker with Python

A **user-friendly GUI application** to track personal expenses, built with Python (Tkinter) and SQLite. Automatically creates new users, categorizes expenses, and provides filtering capabilities.

## ✨ Features

- **User Management**  
  - Automatically registers new users when adding expenses  
  - Tracks expenses separately for each user  

- **Expense Tracking**  
  - Add expenses with amount, category, description, and date  
  - Predefined categories (Food, Transport, Bills, etc.)  
  - Real-time validation of inputs  

- **Smart Filtering**  
  - View all expenses or filter by specific categories  
  - Clean tabular display with totals  

- **Data Persistence**  
  - SQLite database for reliable storage  
  - Proper database schema with foreign keys  

## 🛠️ Tech Stack

- **Frontend**: Tkinter (Python's standard GUI library)  
- **Backend**: SQLite (Lightweight database)  
- **Key Libraries**:  
  - `sqlite3` for database operations  
  - `tkinter` for the graphical interface  
  - `datetime` for expense timestamps  

## 🚀 Installation & Usage

1. **Clone the repository**:
   ```bash
   [git clone https://github.com/your-username/expense-tracker.git](https://github.com/TahaRehan8/py-expense-tracker.git)
   ```

2. **Run the application**:
   ```bash
   python expense_tracker.py
   ```

3. **Using the app**:
   - Enter your username (new users are auto-created)  
   - Add expenses with amount, category, and optional description  
   - Filter expenses using the category dropdown  
   - View all expenses in a scrollable, formatted display  

## 📂 Project Structure

```
expense-tracker/
├── expense_tracker.py  # Main application code
├── expenses.db         # Auto-generated SQLite database
├── README.md           # This file
```

## 🔧 Customization

1. **Add new expense categories**:  
   Modify the `category_entry['values']` list in the code to add/remove categories.

2. **Change database location**:  
   Edit the SQLite connection string to save the database elsewhere.

3. **Extend functionality**:  
   - Add monthly budget alerts  
   - Implement data export (CSV/Excel)  
   - Add charts for spending visualization  

## 🤝 Contributing

Pull requests are welcome! 
