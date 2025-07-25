# 🛠️ Red Team CLI Toolkit – Python Automation for Brute-Force, Lockout & Wordlist Gen

🗓️ **Date:** May 2025  
🧪 **Type:** Offensive Security Mini Project  
💻 **Language:** Python  
🎯 **Focus:** CLI-based Red Team scripts for automation, evasion, and brute-force simulation

---

## 📦 Toolkit Summary

This Python toolkit simulates attacker logic from the command line, bundling 3 modules in a single flag-controlled script:

| Mode (`--tool`)  | Function                         |
|------------------|----------------------------------|
| `1`              | Brute-force password guesser     |
| `2`              | Wordlist generator               |
| `3`              | Login lockout simulator          |

---

## 🚀 How to Run

> Requires: Python 3.x  
> Run using terminal + flags:

python redteam_tool.py --tool 1 --username admin --wordlist pass.txt --silent  
python redteam_tool.py --tool 2 --output list.txt pass123 admin123 welcome1  
python redteam_tool.py --tool 3 --attempts 1234 hunter2 qwerty


---

## 🧪 Sample Output

🔹 **Brute-force (Tool 1):**  
Trying admin:pass123 ✅ Success  
Trying admin:admin123 ❌ Failed  

🔹 **Wordlist Gen (Tool 2):**  
Generated wordlist:  
pass123  
admin123  
welcome1  

🔹 **Lockout Sim (Tool 3):**  
Simulating 3 failed attempts...  
Result: Account locked  

---

## 🧰 Features  
- CLI argument handling via `sys.argv`  
- Simulated brute-force with randomized delays  
- Lockout logic after failed login attempts  
- Wordlist creation from terminal input  
- Optional `--silent` flag for quiet mode  

---

## 📁 Files Included
- `redteam_tool` — Main CLI script  
- `sample_wordlist.txt` — Wordlist input

---

## 🧠 Skills Demonstrated  
- Command-line interface scripting using `sys.argv`  
- Automation of brute-force and lockout simulations  
- Wordlist logic and I/O file handling  
- Flag-based terminal UX like Red Team tools    

---

## ⚠️ Disclaimer  
This project is for educational and ethical testing only.  
Do not use these scripts against any system without proper authorization.
