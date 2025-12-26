# 🧮 Modern Web Calculator

A fully functional, responsive calculator built using Vanilla JavaScript. This project demonstrates the ability to handle mathematical expressions, user input validation, and advanced CSS Grid layouts.

## 🚀 Live Demo
*(Insert your GitHub Pages link here once hosted)*

## ✨ Key Features
- **Standard Arithmetic:** Supports addition, subtraction, multiplication, and division.
- **Error Handling:** Built-in `try-catch` logic to handle invalid expressions (e.g., syntax errors) without crashing the app.
- **Modern UI:** Uses a dark-themed interface with high-contrast operator buttons for better accessibility.
- **Smart Delete:** Includes a "DEL" function to remove the last character and an "AC" function to clear the entire display.
- **Responsive Design:** Utilizes CSS Grid to ensure buttons remain perfectly aligned on all screen sizes.

## 🛠️ Technical Implementation
- **Expression Evaluation:** Uses JavaScript's `eval()` function to parse and calculate string-based mathematical expressions.
- **CSS Grid Layout:** A 4-column grid system used to organize buttons, including specialized "span" properties for the `0` and `=` keys.
- **String Manipulation:** Employs `.slice()` methods for the backspace/delete functionality.

## 📂 Project Structure
```text
Calculator-App/
│
├── index.html    # Calculator structure and button mapping
├── style.css     # CSS Grid layout and glassmorphism effects
└── script.js     # Mathematical logic and error handling
