# 🧪 QA Portfolio: Sliding Tree DOM Component & E2E Testing

> **About this repository:** This project features an interactive sliding DOM tree component accompanied by a robust Quality Assurance setup. It demonstrates expertise in **End-to-End (E2E) UI Testing** using Cypress, alongside strict code styling and architectural validation.

![Cypress](https://img.shields.io/badge/-Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![ESLint](https://img.shields.io/badge/-Static_Analysis-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

## 🎯 Project Overview

The core application is a dynamic, hierarchical DOM component (`src/index.html`, `src/scripts/main.js`, `src/styles/main.scss`) implementing expandable/collapsible sliding tree structures. 

As a **QA Automation Engineer**, my objective in this repository is to validate complex UI interactions, state changes, and user workflows through automated E2E testing rather than manual exploratory verification.

## 🛠️ QA Tech Stack & Tools

* **E2E Testing Framework:** Cypress (`cypress/integration/slidingTreeDom.spec.js`)
* **Static Code Analysis (Shift-Left QA):** ESLint, Stylelint, Prettier
* **CI/CD Pipeline:** GitHub Actions (`.github/workflows/test.yml`)
* **Core Language:** JavaScript (ES6+), SCSS

## 📊 Test Strategy & Coverage

The testing strategy is tailored to verify dynamic DOM behavior:

### 1. End-to-End (E2E) Testing (Cypress)
Located in `cypress/integration/slidingTreeDom.spec.js`, the automated test suite simulates real user actions:
* Verifying tree node expansion and collapse mechanics.
* Checking UI responsiveness and correct rendering of nested DOM elements.
* Validating interactive states and event handlers.

### 2. Architectural & Code Quality Gates
The repository enforces strict development standards via automated pipelines:
* **Linters:** Automatically inspects JavaScript and SCSS code for syntax errors, formatting inconsistencies, and code smells before merging.

## 🚀 How to Run the Tests Locally

To evaluate the E2E test suite and code quality tools on your local machine, follow these steps:

### 1. Environment Setup
Clone the repository and install the dependencies:
```bash
npm install
