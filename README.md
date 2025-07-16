# 🐍 Python CI with GitHub Actions – `appgithubaction` 🚀

This repository demonstrates how to use **GitHub Actions** for setting up a CI workflow in a Python project. It includes a simple math operations module, unit tests with `pytest`, and a CI pipeline using GitHub Actions.

---

## 📁 Folder Structure

```
.github/
└── workflows/
    └── python-app.yml         # ✅ GitHub Actions CI workflow

src/
├── __init__.py
└── math_operations.py         # ➕ Core logic for math operations

tests/
├── __init__.py
└── test_operation.py          # 🧪 Unit tests using pytest

requirements.txt               # 📦 Python dependencies
README.md                      # 📘 Project overview
```

---

## ⚙️ Setup Instructions

### ✅ Install dependencies

```bash
pip install -r requirements.txt
```

### 🧪 Run tests

```bash
pytest tests/
```

---

## 🔁 GitHub Actions Workflow

Located at `.github/workflows/python-app.yml`, the CI pipeline will:

1. 🔄 Trigger on every push & pull request
2. 🐍 Set up Python environment
3. ⚙️ Install dependencies
4. ✅ Run tests using `pytest`

---

## 💡 Example Python Module

```python
# src/math_operations.py
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b
```

---

## 🧠 For Recruiters

This project showcases:

- 📦 Python package structuring
- ✅ Unit testing best practices with `pytest`
- ⚙️ Automated CI/CD using GitHub Actions
- 💼 Clean, production-style organization

---

## 🔗 Connect with Me

📬 [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167/)  
📂 [GitHub Portfolio](https://github.com/Aparna-k246)

---
