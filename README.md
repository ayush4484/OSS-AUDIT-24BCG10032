# 📊 Open Source Audit – Python (OSS Capstone Project)

👨‍🎓 **Student:** Ayush Raj  
🆔 **Registration Number:** 24BCG10032  
📚 **Course:** Open Source Software (OSS NGMC)  
📅 **Submission Date:** 31 March 2026  

---

## 📌 Project Overview

This project is an **Open Source Audit of Python**, analyzing:

- Origin and philosophy of Python  
- Licensing and ethics of open source  
- Linux system integration  
- FOSS ecosystem  
- Comparison with proprietary software  
- Practical shell scripting tasks  

---

## ⚙️ Shell Script Tasks

This project includes **5 Bash scripts** demonstrating Linux + Open Source concepts.

---

## 🧾 Script 1 – System Identity Report

Displays system-level information such as:
- Kernel version  
- User  
- Uptime  
- Distribution  
- Date  

### 📷 Output:
![Script 1 Output](./Screenshot%202026-03-31%20200648.png)

---

## 📦 Script 2 – FOSS Package Inspector

Checks if Python is installed and shows:
- Version  
- Maintainer  
- Description  

### 📷 Output:
![Script 2 Output](./Screenshot%202026-03-31%20200655.png)

---

## 📁 Script 3 – Disk & Permission Auditor

Audits important directories:
- /etc, /var/log, /home, /usr/bin, /tmp  
- Displays permissions and size  
- Checks Python executable location  

### 📷 Output:
![Script 3 Output](./Screenshot%202026-03-31%20200708.png)

---

## 📜 Script 4 – Log File Analyzer

- Reads log file line-by-line  
- Counts keyword occurrences (default: error)  
- Displays last matching lines  

### 📷 Output:
![Script 4 Output](./Screenshot%202026-03-31%20200716.png)

---

## 🧠 Script 5 – Open Source Manifesto Generator

- Takes user input  
- Generates a personalized open-source manifesto  
- Saves output to a .txt file  

### 📷 Output:
![Script 5 Output](./Screenshot%202026-03-31%20200723.png)

---

## ⚠️ Known Issues

- $'\r': command not found → Windows line endings issue  
- read: -p: not a valid identifier → shell compatibility  
- Syntax errors in loops  

### ✅ Fix:

```
dos2unix script.sh
chmod +x script.sh
./script.sh
```

---

## 🧠 Key Learnings

- Open source promotes freedom, collaboration, and transparency  
- Python is deeply integrated into Linux systems  
- Bash scripting helps in automation & system auditing  
- Understanding permissions is critical for system security  

---

## 🚀 Conclusion

This project demonstrates how open source software like Python powers modern computing and enables flexible development.

---

## 📌 Repository Structure

```
.
├── README.md
├── report.pdf
├── script1.sh
├── script2.sh
├── script3.sh
├── script4.sh
├── script5.sh
└── screenshots/
```
