# 🧮 Smart Calculator

A responsive and visually appealing **calculator web app** built using **HTML**, **Tailwind CSS**, and **JavaScript**. It performs basic arithmetic operations with a modern, gradient-themed interface.

---

## 📋 Description

This **Smart Calculator** allows users to perform arithmetic calculations such as addition, subtraction, multiplication, and division. It supports parentheses, decimal points, and evaluates expressions dynamically using JavaScript's `eval()` function.

The user interface is styled using **Tailwind CSS**, giving it a vibrant, mobile-friendly look with hover effects, rounded buttons, and shadows.

---

## ✅ Features

- ➕ Addition  
- ➖ Subtraction  
- ✖️ Multiplication  
- ➗ Division  
- ( ) Parentheses support  
- 📍 Decimal point input  
- 🧼 Clear button (C)  
- ✅ Real-time evaluation with `=`  
- 🖌️ Stylish UI using Tailwind CSS  
- 🔁 Smart auto-clear on next input after evaluation

---

## 🚀 How to Run

1. Clone or download the project.
2. Open `index.html` in any modern web browser.
3. Use the on-screen buttons to input your calculation.
4. Click `=` to evaluate the result.
5. Press `C` to clear the display.

---

## 🧠 How It Works

- The display is a read-only text input updated via button clicks.
- Symbols like `×`, `÷`, and `−` are mapped to `*`, `/`, and `-` for JavaScript evaluation.
- `eval()` handles the math expression parsing and calculation.
- A reset flag clears the display on the next input after getting a result or error.

---
