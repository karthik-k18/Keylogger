# Keylogger
This project is a Python-based keylogger developed strictly for ethical and educational purposes. The main objective is to demonstrate how keyloggers function so that students, cybersecurity learners, and developers can understand potential threats and design stronger security mechanisms against such attacks. The keylogger captures every keystroke entered on the keyboard and logs it to a timestamped text file, which is saved locally in a secure logs directory.

The script uses the pynput library to listen to keyboard events in real time. It supports both printable and special keys (e.g., Enter, Backspace, Shift), and safely exits logging when the ESC key is pressed. All logs are stored with timestamps, and the script can be extended to include alert mechanisms, encryption, or email-based log reporting for research and simulation purposes.

⚠️ Disclaimer: This tool is created strictly for educational use. Using keyloggers without the user's knowledge or consent is illegal and unethical. Always obtain proper authorization when demonstrating or testing this tool.

🎯 Key Features:
Real-time keystroke logging using pynput

Logs both character and special keys

Automatically saves logs in a timestamped .txt file

Press ESC to safely stop the logger

Lightweight, portable, and easy to extend

Folder-based log organization (/logs)

🧰 Tech Stack / Requirements:
Python 3.x

pynput library (Install with: pip install pynput)

OS file access (for log writing)

🎯 Learning Objectives:
Understand how malicious keyloggers operate

Learn ethical hacking and penetration testing techniques

Improve security awareness and defensive coding practices

Build foundational skills in cybersecurity and threat analysis
