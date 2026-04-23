# 🧪 Trello Automation using Playwright

This project is an end-to-end automation testing framework built using Playwright with Node.js. It automates Trello workflows like login, board creation, list and card management, and validations.

## 🚀 Tech Stack
- Node.js
- Playwright
- JavaScript / TypeScript
- Git & GitHub

## 📁 Project Structure
tests/               # Test cases
playwright.config.ts # Playwright configuration
test-results/        # Test execution results (ignored in Git)
playwright-report/   # HTML reports (ignored in Git)
.env                 # Environment variables (ignored in Git)

## ⚙️ Setup Instructions

### 1. Clone repository
git clone https://github.com/itssdrishtiii/trello-automation.git
cd trello-automation

### 2. Install dependencies
npm install

### 3. Install Playwright browsers
npx playwright install

### 4. Create .env file
TRELLO_EMAIL=your_email@example.com
TRELLO_PASSWORD=your_password

## ▶️ Run Tests
npx playwright test

Run headed mode:
npx playwright test --headed

Run specific file:
npx playwright test tests/trello.spec.ts

## 📊 View Report
npx playwright show-report

## 📦 Features Automated
- Login to Trello
- Create Board (QA Scrum Board)
- Create Lists (To Do, In Progress, Done)
- Add Cards
- Validate board structure
- Labels and attachments

## 🚫 Ignored Files
node_modules/
playwright-report/
test-results/
.env
sample.pdf

## 🧠 Key Learnings
- Playwright UI automation
- End-to-end testing
- Git & GitHub workflow
- Test reporting

## 👩‍💻 Author
Drishti  
QA Automation Engineer (Trainee)

## 📌 Note
This project is for QA automation practice and SDET learning.
