# 🛠️ Red Team CLI Toolkit – Python Automation for Brute-Force, Lockout & Wordlist Gen

🗓️ **Date:** July 2025  
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

🚀 How to Run
Requires: Python 3.x
Run using terminal + flags:

bash
Copy
Edit
python hacker_toolkit_v2.py --tool 1 --username admin --wordlist pass.txt --silent  
python hacker_toolkit_v2.py --tool 2 --output list.txt pass123 admin123 welcome1  
python hacker_toolkit_v2.py --tool 3 --attempts 1234 hunter2 qwerty
📂 Files Included
hacker_toolkit_v2.py — Main CLI toolkit

sample_wordlist.txt (optional) — Wordlist input/output

🧪 Sample Outputs
🔹 Brute-force Mode (Tool 1):
pgsql
Copy
Edit
Trying admin:pass123 ✅ Success  
Trying admin:admin123 ❌ Failed  
🔹 Wordlist Generator (Tool 2):
yaml
Copy
Edit
Generated wordlist:  
pass123  
admin123  
welcome1  
🔹 Lockout Simulator (Tool 3):
makefile
Copy
Edit
Simulating 3 failed attempts...  
Result: Account locked  
🧠 Skills Demonstrated
Command-line interface (argparse) design

Automation of brute-force and lockout simulations

Wordlist logic and I/O file handling

Python scripting with flags and silent mode logic

⚠️ Disclaimer
This toolkit is for educational and ethical testing only.
Do not use it on systems without proper permission.
