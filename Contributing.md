# Contributing to Web Calculator

Thank you for your interest in contributing to the **Web Calculator** project! Open-source contributions, bug fixes, feature proposals, and documentation enhancements are highly welcome.

Please take a moment to review this document to ensure a smooth collaboration process.

---

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
  - [Reporting Bugs](#1-reporting-bugs)
  - [Suggesting Features](#2-suggesting-features)
  - [Pull Requests](#3-submitting-pull-requests)
- [Development Setup](#-development-setup)
- [Coding Conventions](#-coding-conventions)

---

## 🤝 Code of Conduct

Please foster an inclusive and respectful environment. Be respectful, constructive, and civil in all project communications (issues, pull requests, and discussions).

---

## 🚀 How Can I Contribute?

### 1. Reporting Bugs

Before creating a new bug report, please check existing open [Issues](https://github.com/adarsh0707-kumar/Calculator/issues) to avoid duplicates.

When filing an issue, please include:
- **A clear summary title**.
- **Steps to reproduce** the bug.
- **Expected result** vs **Actual result**.
- **Browser/Environment details** (e.g., Chrome v120 on Windows 11).
- **Screenshots or screen recordings** if relevant.

### 2. Suggesting Features

Feature requests and enhancement ideas are welcomed! Please open an issue titled with `[Feature Request]: Your feature idea` and explain:
- What problem the feature solves or what value it adds.
- Proposed implementation details or design mockups (if applicable).

### 3. Submitting Pull Requests

1. **Fork the Repository**:
   Click the **Fork** button at the top-right corner of the GitHub page.

2. **Clone your Fork locally**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Calculator.git
   cd Calculator
   ```

3. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/amazing-new-feature
   ```

4. **Make Your Changes**:
   Implement your fixes, feature extensions, or documentation updates.

5. **Test Your Work**:
   Ensure calculations execute correctly across edge cases (e.g., division by zero, consecutive operator clicks, decimal precision). Test responsiveness across desktop and mobile screen sizes.

6. **Commit Your Changes**:
   Use descriptive commit messages following standard conventions:
   ```bash
   git commit -m "Feat: Add full keyboard input listener support"
   ```

7. **Push to GitHub**:
   ```bash
   git push origin feature/amazing-new-feature
   ```

8. **Open a Pull Request**:
   Go to the original repository and open a Pull Request from your feature branch into `main`. Provide a concise summary of the changes made.

---

## 🛠️ Development Setup

Because this project relies exclusively on client-side native web standards, setting up the local environment is straightforward:

1. Clone your fork.
2. Edit `index.html`, `style.css`, or `script.js` directly using your preferred IDE (e.g., VS Code, WebStorm, Sublime Text).
3. Open `index.html` in your browser to verify changes instantly.

---

## 🎨 Coding Conventions

To maintain clean and readable code across the codebase, please follow these guidelines:

- **HTML**: Use clean semantic elements and concise class naming.
- **CSS**: 
  - Keep styling modular and organized.
  - Ensure mobile-first responsiveness or CSS grid/flexbox patterns.
- **JavaScript**:
  - Write clean ES6+ code (`const`/`let`, arrow functions, template literals).
  - Use clear, self-explanatory variable and function names.
  - Avoid unnecessary external third-party dependencies unless strictly required.

---

Thank you for contributing! Happy Coding! 🚀