# 🧮 Java Calculator

> A fully functional GUI calculator built with Java Swing — clean layout, real-time input, and full arithmetic support.

---

## 🖥️ About

A desktop calculator application built from scratch using Java AWT and Swing. It features a responsive button grid, real-time display, and handles all standard arithmetic operations including negation and decimal input.

---

## ✨ Features

- Addition, Subtraction, Multiplication, Division
- Decimal point support
- Toggle positive/negative `(-)`
- Backspace `Del` — removes the last digit
- Clear `Clr` — resets the display
- Clean 4×4 button grid layout
- Custom font rendering (`Jersey 25`)

---

## 🗂️ Project Structure

```
javaCalculator/
└── calculator.java    # Single-file app — UI + logic + event handling
```

---

## 🚀 Setup & Run

### Prerequisites
- Java JDK 8+

### Compile & Run

```bash
javac calculator.java
java calculator
```

The calculator window opens immediately — no config needed.

---

## 🔧 How It Works

The app implements `ActionListener` on a single class. Each button press either appends a digit/decimal to the display, stores the first operand and operator, or evaluates and displays the result. The `Del` button slices the last character from the display string; `(-)` multiplies the current value by `-1`.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Language | Java |
| GUI | `javax.swing`, `java.awt` |
| Event handling | `ActionListener` |
| Layout | `GridLayout` + absolute bounds |

---

## 📄 License

Open source — free to use and modify.

---

*Built by [Pravin Kumar M](https://github.com/Pravinpk26)*
