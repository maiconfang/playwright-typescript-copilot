# 🎭 playwright-typescript-copilot

This project is a structured example of how to build end-to-end (E2E) tests using **Playwright**, **TypeScript**, and **Page Object Model (POM)** — with the help of **GitHub Copilot**.

---

## 📌 Project Goals

- Automate the login screen of an Angular application (`http://localhost:4200/#/login`)
- Apply good practices with Playwright and POM
- Explore how GitHub Copilot can assist in writing reusable and clean test code

---

## 📁 Project Structure

```
├── config/
│   └── testConfig.ts          # Optional shared config (placeholder for now)
├── pages/
│   └── LoginPage.ts           # Page Object for login functionality
├── tests/
│   └── login.spec.ts          # Test file for login scenarios
├── package.json               # Dependencies and scripts
├── playwright.config.ts       # Playwright global config (to be added later)
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Install dependencies

```bash
npm install
```

### Run all tests

```bash
npx playwright test
```

---

## 💡 GitHub Copilot Usage

Some parts of this project were assisted by [GitHub Copilot](https://github.com/features/copilot), such as:

- Generating the initial `LoginPage.ts` with Playwright best practices
- Creating assertions for error messages
- Refactoring code into clean POM structure

> I may update or remove this section in the future. 😄

---

## ✅ Technologies

- [Playwright](https://playwright.dev)
- TypeScript
- GitHub Copilot (assistive AI)
