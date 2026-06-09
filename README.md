# 🔐 Login & Registration System

A simple console-based authentication system built in **C++** that stores user credentials in a text file.

---

## Features
- Register a new account with username & password
- Login with credential validation
- Duplicate username check
- Input length validation
- Handles invalid inputs without crashing

---

## Run It

**Compile:**
```bash
g++ main.cpp -o login_system
```

**Execute:**
```bash
./login_system        # Linux/macOS
login_system.exe      # Windows
```

---

## Project Structure
```
├── main.cpp       # Source code
├── users.txt      # Auto-generated credentials file
└── README.md
```

> ⚠️ Add `users.txt` to `.gitignore` — it stores passwords in plain text!

---
