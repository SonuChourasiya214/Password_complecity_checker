# 🔐 Password Complexity Checker

A simple and effective Password Complexity Checker built using Python.
This tool evaluates the strength of a password based on multiple security criteria and provides clear feedback to help users create strong and secure passwords.

---

## 📌 Features

* Checks password **length**
* Detects **uppercase** letters
* Detects **lowercase** letters
* Checks for **numbers**
* Validates **special characters**
* Provides **strength rating** (Weak / Medium / Strong)
* Gives **improvement suggestions**

---

## 🛠️ Technologies Used

* **Python 3**
* **re module** (Regular Expressions)

---

## 🧠 Password Strength Logic

| Criteria           | Description                 |
| ------------------ | --------------------------- |
| Length             | Minimum 8 characters        |
| Uppercase          | At least one capital letter |
| Lowercase          | At least one small letter   |
| Numbers            | At least one digit          |
| Special Characters | Symbols like `@ # $ %`      |

### Strength Levels

* **Weak** → 1–2 conditions met
* **Medium** → 3–4 conditions met
* **Strong** → All conditions met

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/SonuChourasiya214/password-complexity-checker.git
```

2. Navigate to the project folder

```bash
cd password-complexity-checker
```

3. Run the script

```bash
python password_checker.py
```

---

## 🧪 Sample Output

```
Enter your password: Test@123

Password Strength: Strong
Your password is very strong! ✅
```

---

## 📂 Project Structure

```
password-complexity-checker/
│
├── password_checker.py
├── README.md
```
## 📚 Learning Outcomes

* Python fundamentals
* Regular expressions
* Input validation
* Security best practices
* Password policies

---

## 🧑‍💻 Author

**Sonu Choursiya**
Cybersecurity Enthusiast | Ethical Hacking Learner

---
