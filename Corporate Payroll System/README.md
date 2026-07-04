# Corporate Talent & Payroll Management System

##  Project Description

This project is a Python-based Corporate Payroll System that simulates how companies calculate employee salaries.
It is built using modular programming by dividing the logic into separate functions.

The system takes employee details such as name, department, salary, and performance rating, then calculates bonus, tax, and final net salary.

---

##  Project Goal

The goal of this project is to:

* Practice writing reusable Python functions
* Apply conditional logic (if / elif / else)
* Validate user input
* Build a structured and clean program

---

##  Features

* Calculate bonus based on employee performance
* Calculate tax based on salary range
* Input validation for correct data
* Display a formatted payroll summary

---

##  System Logic

### 🔹 Bonus Calculation

* Rating = 5 → 20% bonus
* Rating = 3 or 4 → 10% bonus
* Rating < 3 → No bonus

### 🔹 Tax Calculation

* Gross Salary > 7000 → 15% tax
* Between 3000 and 7000 → 10% tax
* Below 3000 → No tax

---

##  How to Run

1. Make sure Python is installed on your machine
2. Download the project files
3. Run the following command:

```bash
python main.py
```

---

##  Example Run

```
--- Corporate Payroll System ---
Enter Employee Name: Malak
Enter Department: AI
Enter Base Salary (EGP): 5000
Enter Performance Rating (1-5): 4

========================================
PAYROLL STATEMENT FOR: Malak
Department: AI
========================================
• Base Salary: 5000.00 EGP
• Earned Bonus: 500.00 EGP
• Tax Deductions: 550.00 EGP
----------------------------------------
NET PAYABLE CASH: 4950.00 EGP
========================================
```
