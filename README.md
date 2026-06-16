# CodeAlpha - Secure Coding Review 

## Task 3: Secure Coding Review | CodeAlpha Cybersecurity Internship

---

## Project Overview
This project performs a **security audit** on a deliberately vulnerable Python Flask web application.
It demonstrates how to identify, analyze, and fix common security vulnerabilities found in real-world applications.

---

##  Vulnerabilities Found

| ID | Vulnerability | Severity |
|----|--------------|----------|
| V001 | SQL Injection | 🔴 Critical |
| V002 | Hardcoded Credentials | 🟠 High |
| V003 | Weak Hashing (MD5) | 🟠 High |
| V004 | Cross-Site Scripting (XSS) | 🟠 High |
| V005 | Path Traversal | 🔴 Critical |
| V006 | Debug Mode Enabled | 🟡 Medium |
| V007 | Sensitive Data Exposure | 🟠 High |

---

## 📁 Project Structure
CodeAlpha_SecureCodingReview/

├── vulnerable_app.py       # Deliberately vulnerable Flask app

├── security_scanner.py     # Static analysis scanner tool

├── security_report.html    # Full audit report with fixes

└── README.md               # Project documentation

---

##  How to Run

### 1. Install dependencies
```bash
pip install flask
```

### 2. Run the vulnerable app
```bash
python vulnerable_app.py
```

### 3. Run the security scanner
```bash
python security_scanner.py vulnerable_app.py
```

### 4. View the report
Open `security_report.html` in your browser.

---

## 🔧 Tools Used
- Python 3
- Flask
- Custom Static Analysis Scanner
- Manual Code Review

---

##  Author
- **Intern:** akshmurali07
- **Domain:** Cybersecurity
