# 🚀 Email Alias Generator

A colorful, terminal-based Python tool that generates disposable **email aliases** for Gmail users using creative styles like `+tags`, random strings, and dotted formats. Perfect for filtering spam, organizing your inbox, or signing up for websites with unique addresses.

![Python](https://img.shields.io/badge/Python-3.6%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-green)
![License](https://img.shields.io/github/license/root60/Email-Alias-Generator)

---

## ✨ Features

- ✅ Generates unique email aliases using:
  - Gmail `+tag` style
  - Random suffixes
  - Dotted addresses (Gmail ignores dots)
- ✅ Saves aliases to a `.txt` file
- ✅ Cross-platform: Works on **Windows**, **Linux**, and **macOS**
- ✅ Clean, interactive CLI with colorful output (thanks to `colorama`)
- ✅ Emoji and ASCII-art terminal interface for fun and clarity

---

## 📸 Preview

```
┌────────────────────────────────────────────┐
│           🚀 Email Alias Generator         │
│               Author: RedHydra             │
└────────────────────────────────────────────┘

📧 Enter your email (e.g., user@gmail.com): example@gmail.com
🔢 How many aliases do you need?: 5

⚡ Generating aliases...

📦 Generated Email Aliases:
1. example+abc12@gmail.com
2. exa.mpl.e@gmail.com
3. example3d9z1@gmail.com
...
```

---

## 🛠️ Installation

### Prerequisites

- Python 3.6 or newer
- pip (Python package manager)

### Install dependencies

```bash
pip install -r requirements.txt
```

> `colorama` is required for colorful terminal output.

---

## 🚀 Usage

```bash
python EmailAliasGenerator.py
```

Then follow the prompts to:
- Enter your base Gmail address
- Choose how many aliases you want
- View and optionally save the generated aliases

---

## 📂 Output

All generated aliases can be saved in a file named:

```
email_aliases.txt
```

---

## 🧠 How it Works

The generator randomly picks one of the following styles for each alias:
- `username+randomstring@gmail.com`
- `u.s.e.r.n.a.m.e@gmail.com`
- `usernamerandomstring@gmail.com`

All formats route to the same inbox if you're using Gmail, making them great for filtering and tracking.

---

## 🧑‍💻 Author

**RedHydra** ([@root60](https://github.com/root60))  
Passionate about privacy tools, open-source utilities, and clean terminal UI experiences.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributions

Feel free to fork the repo, submit pull requests, or open issues!
