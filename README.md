# 🧮 Interactive Web Calculator

A clean, responsive, and light-weight web-based calculator built using vanilla modern web standards (**HTML5**, **CSS3**, and **JavaScript**). This application provides essential arithmetic functionality alongside clear input handling, optimized layout responsiveness, and clean interactive feedback.

---

## 📸 Overview

The **Web Calculator** provides an intuitive digital interface mimicking physical electronic calculators while taking advantage of fluid web responsive design. It processes arithmetic expressions seamlessly and handles edge cases safely.

---

## ✨ Features & Functionality

- **Core Operations**:
  - Addition (`+`), Subtraction (`-`), Multiplication (`*`), and Division (`/`).
  - Decimal point (`.`) entry for precision calculations.
  - Evaluation (`=`) execution.
- **Display & State Management**:
  - **All Clear (`AC`)**: Resets the entire calculator state and clears the display buffer.
  - **Delete (`DEL`)**: Erases the last inputted character or operator.
  - Continuous evaluation support for long mathematical expressions.
- **Responsive Layout**:
  - Adaptive CSS grid/flexbox interface tailored for desktops, tablets, and mobile screens.
  - Clean button focus states and active tactile feedback.
- **Zero External Dependencies**:
  - Built purely with standard web technologies—no heavy frameworks or runtime bundle overhead.

---

## 🛠️ Tech Stack & Architecture

- **[HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)**: Semantic structure and accessible DOM elements.
- **[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)**: Custom styling, flexbox/grid layout systems, hover effects, and responsive breakpoints.
- **[JavaScript (ES6+)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**: Event listening, state tracking, string parsing, arithmetic evaluations, and DOM manipulation.

---

## 📁 Repository Structure

```text
Calculator/
├── index.html     # Main markup defining calculator layout and structure
├── style.css      # Visual aesthetics, layout styling, and responsiveness
├── script.js      # Core logic, button event listeners, and calculation engine
├── README.md      # Detailed project overview and instructions
└── CONTRIBUTING.md# Guidelines for open-source contributions
```

---

## 🚀 Getting Started

### Prerequisites

No build tools or command-line package managers are needed! All you need is any modern browser (Chrome, Firefox, Edge, Safari, Brave, Opera, etc.).

### Installation & Local Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/adarsh0707-kumar/Calculator.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Calculator
   ```

3. **Launch the Application**:
   - Double-click `index.html` to open it in your default web browser.
   - Alternatively, if you use **Visual Studio Code**, launch it with the **Live Server** extension for real-time live reloading.

---

## 🧪 Usage Example

1. **Basic Operations**: Click numbers followed by operators to build an expression (e.g., `1` `2` `+` `8` `=`).
2. **Correcting Mistakes**: Use the `DEL` button to delete the last character entered without resetting the current calculation.
3. **Starting Fresh**: Press `AC` at any time to clear all current operations and values.

---

## 🗺️ Roadmap & Proposed Enhancements

- [ ] Add keyboard listener support (numpad and standard keyboard input).
- [ ] Implement scientific calculator functions (square root, trigonometric functions, powers, logarithms).
- [ ] Add dark/light mode theme toggle switch.
- [ ] Implement calculation history log panel.

---

## 👤 Author

- **Adarsh Kumar** - [*@adarsh0707-kumar*](https://github.com/adarsh0707-kumar)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to use, modify, and distribute it for personal or educational purposes.