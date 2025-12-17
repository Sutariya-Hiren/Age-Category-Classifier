# Age Category Classifier

This is a simple beginner-level Python project that classifies a person's age
into different categories such as Child, Teenager, Adult, or Senior using
if-else conditions.

## 🚀 Features
- Uses simple if-else logic
- Displays age category:
  - Child
  - Teenager
  - Adult
  - Senior

## 🛠 Technologies Used
- Python

## 📌 How It Works
- If age is less than 13 → Child
- If age is less than 20 → Teenager
- If age is less than 60 → Adult
- Otherwise → Senior

## ▶️ Example Code
```python
age = 18

if age < 13:
    print("You're a child")
elif age < 20:
    print("You're a Teenager")
elif age < 60:
    print("You're an Adult")
else:
    print("You're a Senior")
