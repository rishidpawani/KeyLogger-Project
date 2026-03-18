# 🔐 Enhanced Keylogger with Special Key Handling

> **Educational Project** | Pillai College | Cybersecurity

---

## ⚠️ Disclaimer

This project is developed **strictly for educational purposes** as part of a college cybersecurity assignment. It is intended to demonstrate how keyboard input monitoring works at a programming level. **Do not use this on any device without explicit permission from the owner.** Unauthorized use of keyloggers is illegal and unethical.

---

## 📌 Overview

This project implements an enhanced keylogger in Python using the `pynput` library. It captures keyboard input and logs it to a file, with specific handling for special keys such as space, enter, shift, control, and backspace — producing clean, readable logs.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Library:** `pynput`

---

## ✨ Features

- Captures real-time keystrokes
- Handles special keys:
  - `Space` → logged as a space character
  - `Enter` → logged as a new line
  - `Shift` / `Control` → ignored (no clutter)
  - `Backspace` → logged as `()` to indicate deletion
- Saves all keystrokes to `keyfile.txt`
- Simple, modular, and readable code

---

## 📁 Project Structure

```
keylogger-project/
│
├── keylog.py                          # Main keylogger script
├── KeyLogger_Cybersecurity_Project.pdf  # College project documentation
├── .gitignore                         # Excludes keyfile.txt from commits
└── README.md                          # This file
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/keylogger-project.git
   cd keylogger-project
   ```

2. **Install the required library**
   ```bash
   pip install pynput
   ```

3. **Run the script** *(only on your own machine)*
   ```bash
   python keylog.py
   ```

4. **View the log**
   ```bash
   cat keyfile.txt
   ```

5. **Stop the logger** — Press `Ctrl+C` in the terminal.

---

## 📄 Sample Output

```
Hello ()World
My Name is Rishi
```
> `()` represents a backspace/deleted character.

---

## 📚 Key Learnings

- How Python's `pynput` library interacts with OS-level keyboard events
- Handling and filtering special keys programmatically
- Importance of ethical considerations in cybersecurity tools

---

## 🎓 Academic Context

| Field       | Details                              |
|-------------|--------------------------------------|
| Student     | Rishi Devesh Pawani                  |
| College     | Pillai College of Arts, Commerce & Science |
| Subject     | Cybersecurity                        |
| Project Type | Lab Assignment                      |

---

## 📜 License

This project is for **educational use only**. Any malicious use is strictly prohibited and the author holds no responsibility for misuse.
