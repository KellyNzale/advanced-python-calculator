# 🧮 Advanced Python Calculator

This is a terminal-based advanced calculator built in Python as part of a graduate-level Software Engineering midterm. The project demonstrates the use of **software design patterns**, **modular architecture**, **logging**, **environment variables**, **test coverage**, and **CI/CD with GitHub Actions**.

---

## 🎬 Video Demo

👉 [Watch the Demo Video](https://youtube.com/shorts/YCwXX0E68PY?si=gasB3POWrmU4-4oy)

---

## 🛠️ Features

- ✅ Basic operations: `add`, `sub`, `mul`, `div`
- ➕ Plugin system to support new commands like `mod`
- 📜 History management (view, save, clear) using Pandas
- 🧪 Exception handling with both EAFP and LBYL styles
- 🗂️ Structured codebase with `main.py`, `repl.py`, and plugins
- 🧾 Professional logging stored in `logs/app.log`
- ⚙️ Environment-based configuration via `.env`
- 🚀 CI pipeline with GitHub Actions
- 📈 Test coverage with `pytest` and code quality enforced by `pylint`

---

## 🧩 Design Patterns Used

| Pattern      | Description |
|--------------|-------------|
| **Command**  | Handles user commands in REPL via a dictionary of functions |
| **Facade**   | `HistoryManager` provides a simplified interface to manage Pandas history |
| **Plugin (Strategy)** | Supports dynamic addition of operations (e.g., `mod`) |
| **Singleton (optional)** | Could be implemented for managing log or configuration |

> 📌 See actual pattern implementation in [main.py](main.py), [repl.py](repl.py), and `plugins/`.

---

## 📁 Project Structure

