# Expense-Tracker

# 💎 gemFin - Personal Finance Management System

gemFin is a web-based personal finance management application that helps users track their income, expenses, budgets, savings goals, and financial reports in one place.

The project is built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**, providing an intuitive interface for managing personal finances and improving financial awareness.

---

## 🚀 Features

### 👤 User Authentication

* User registration and login system
* Secure password hashing using PHP's password hashing functions
* Session-based authentication
* Logout functionality

### 💰 Transaction Management

* Add income and expense transactions
* Categorize transactions
* Record transaction descriptions and dates
* Prevent future-dated transactions
* Automatic balance updates

### 📊 Dashboard

* Overview of financial activity
* Current balance tracking
* Quick access to financial data
* Transaction summaries

### 📁 Budget Management

* Create custom expense categories
* Set monthly budgets
* Track spending against budgets
* View budget performance by month

### 🎯 Savings Goals

* Create savings goals with target amounts
* Set target completion dates
* Add contributions toward goals
* Track goal progress
* Goal completion indicators

### 📈 Financial Reports

* Income vs Expense analysis
* Monthly financial trends
* Custom date range filtering
* Yearly and historical reports

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Font Awesome

### Backend

* PHP

### Database

* MySQL

---

## 📂 Project Structure

```text
gemFin/
│
├── index.php           # Login page
├── register.php        # User registration
├── dashboard.php       # Main dashboard
├── budgets.php         # Budget management
├── goals.php           # Savings goals
├── reports.php         # Financial reports
├── logout.php          # Logout functionality
├── db_connect.php      # Database connection
├── schema.sql          # Database schema
├── gemfin.sql          # Database dump
│
├── css/
│   └── style.css
│
└── sidebar.php
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemFin.git
cd gemFin
```

### 2. Create Database

Create a MySQL database:

```sql
CREATE DATABASE gemfin;
```

### 3. Import Database

Import either:

```text
schema.sql
```

or

```text
gemfin.sql
```

into your MySQL database.

### 4. Configure Database Connection

Update database credentials in:

```php
db_connect.php
```

Example:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "gemfin";
```

### 5. Run the Project

Place the project inside:

```text
htdocs/       (XAMPP)
```

or

```text
www/          (WAMP)
```

Start Apache and MySQL, then visit:

```text
http://localhost/gemFin
```

---

## 🔒 Security Features

* Password hashing
* Session authentication
* Prepared statements for critical operations
* User-specific financial data access

---

## 🎯 Future Improvements

* Email verification
* Expense analytics dashboard
* Export reports to PDF/Excel
* Recurring transactions
* Mobile responsive design improvements
* Notification and reminder system
* AI-powered spending insights

---

Developed as a personal finance management project to help users monitor spending, manage budgets, and achieve savings goals.

---

## 📄 License

This project is intended for educational and learning purposes.
