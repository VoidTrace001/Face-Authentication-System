# 🤝 Contributing to Face Authentication System

Thank you for your interest in contributing! Here's how you can help improve this project.

---

## 📋 How to Contribute

### 1. Fork the Repository

Click the **Fork** button at the top right of the repo page.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/Face-Authentication-System.git
cd Face-Authentication-System
```

### 3. Create a Branch

Always create a new branch for your changes — never commit directly to `main`.

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

### 4. Set Up Your Environment

```bash
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 5. Make Your Changes

- Keep code clean and readable.
- Follow PEP 8 Python style guidelines.
- Add comments where the logic isn't immediately obvious.

### 6. Test Your Changes

Run the main script and make sure nothing is broken:

```bash
python main.py
```

### 7. Commit Your Changes

Write a clear, descriptive commit message:

```bash
git add .
git commit -m "feat: add multi-face detection support"
```

### 8. Push and Open a Pull Request

```bash
git push origin feature/your-feature-name
```

Then go to GitHub and open a **Pull Request** to the `main` branch.

---

## ✅ Contribution Guidelines

- **Bug fixes** – Always welcome! Please describe what was broken and how you fixed it.
- **New features** – Open an issue first to discuss before building.
- **Documentation** – Improvements to README, comments, or this file are always appreciated.
- **Do NOT commit** face images or personal data to the repository.
- **Do NOT commit** `__pycache__/`, `venv/`, or `.env` files.

---

## 🐛 Reporting Bugs

Please open a [GitHub Issue](https://github.com/VoidTrace001/Face-Authentication-System/issues) with:

1. A clear title
2. Steps to reproduce the bug
3. Expected vs actual behavior
4. Your OS, Python version, and library versions

---

## 💬 Suggesting Enhancements

Open an issue with the label `enhancement` and describe:
- What the feature does
- Why it would be useful
- Any implementation ideas you have

---

Thanks for contributing! 🙌
