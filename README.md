# static-code-analysis
Overview
This project is part of Lab 5: Static Code Analysis, aimed at improving Python code quality, security, and maintainability using Pylint, Flake8, and Bandit.
The lab involves analyzing an initial version of inventory_system.py, identifying issues, fixing them, and verifying the fixes through static analysis tools.

🎯 Objectives
Understand the purpose of static code analysis.

Detect and fix common Python issues:

Mutable default arguments

Broad exception handling

Unsafe functions (eval)

File handling and input validation

Apply fixes and re-run analysis tools until the code is clean.

🛠️ Tools Used
Tool	Purpose
Pylint	Detects logical and style issues.
Flake8	Ensures PEP 8 style compliance.
Bandit	Finds security vulnerabilities.

Install all tools using:
pip install pylint flake8 bandit

Running Static Analysis
After setting up your environment (e.g., GitHub Codespaces), run the following commands:
# Run Pylint
pylint inventory_system.py > pylint_report.txt

# Run Bandit
bandit -r inventory_system.py > bandit_report.txt

# Run Flake8
flake8 inventory_system.py > flake8_report.txt


Project Structure
.
├── inventory_system.py        # Fixed version of the code
├── pylint_report.txt           # Output of Pylint
├── flake8_report.txt           # Output of Flake8
├── bandit_report.txt           # Output of Bandit
├── reflection.md               # Reflection answers
└── README.md                   # This file
