# 🛡️ SQL Injection Lab

A hands-on lab demonstrating SQL injection vulnerabilities and how to defend against them. This project simulates both insecure and secure SQL query handling, ideal for showcasing offensive and defensive cybersecurity skills.

---

## 📅 Date

2025-06-04

---

## 🧠 Skills Demonstrated

- Identifying SQL injection vulnerabilities
- Crafting malicious input to exploit queries
- Mitigating attacks using parameterized queries
- Analyzing application behavior and query structure

---

## ⚙️ Tools & Technologies

- SQL (SQLite/MySQL syntax)
- Python (for simulating inputs)
- OWASP Top 10 reference
- VS Code / Terminal

---

## 🚨 Lab Scenario

🧪 A small web app uses insecure SQL queries to log users in.  
🎯 You test the login with the input `' OR 1=1 --` and successfully bypass authentication.  
🔐 You then rewrite the query using parameterized queries (e.g. `?` placeholders) to prevent injection.  
✅ Attack blocked. App now only allows legitimate logins.

---

## 📁 Files

- `vulnerable_query.sql`: The unsafe query
- `secure_query.sql`: The fixed, parameterized version
- `injection_test.py`: Script to test the injection
- `screenshots/`: Before & after login attempts

---

## 📝 Notes

Use this lab to explain SQL injection in interviews.  
It shows you understand both **how attacks work** and **how to fix them.**

---

## 🔗 References

- [OWASP SQL Injection Guide](https://owasp.org/www-community/attacks/SQL_Injection)
