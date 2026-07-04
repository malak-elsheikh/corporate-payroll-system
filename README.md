# Corporate Payroll System 

##  Overview
This is a simple Python-based payroll system that calculates employee salary details including bonus, tax deductions, and net salary based on performance rating and base salary.

##  Project Purpose
The goal of this project is to practice:
- Python functions
- Conditional statements (if-elif-else)
- User input handling
- Basic financial calculations
- Clean output formatting

##  How It Works
1. The user enters:
   - Employee name
   - Department
   - Base salary
   - Performance rating (1–5)

2. The system calculates:
   - Bonus based on performance rating
   - Gross salary (base + bonus)
   - Tax deductions based on salary range
   - Net salary after deductions

3. The program prints a structured payroll statement.

##  Calculation Rules

### Bonus:
- Rating = 5 → 20% bonus
- Rating ≥ 3 → 10% bonus
- Otherwise → no bonus

### Tax:
- Salary > 7000 → 15% tax
- Salary ≥ 3000 → 10% tax
- Otherwise → no tax

##  How to Run
```bash
python main.py
