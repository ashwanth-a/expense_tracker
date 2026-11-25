# Income and Expense Tracker

A browser-based personal finance tracker built with HTML, CSS and vanilla JavaScript. It helps users record income and expenses, set category budgets, review charts and track savings goals.

## Features

- Dashboard with balance, monthly income, expenses and savings rate
- Add, edit and delete income/expense transactions
- Filter transactions by type, category and month
- Search transactions by description or category
- Budget categories with monthly spending progress
- Reports and charts powered by Chart.js
- Savings goals and linked contributions
- Light/dark theme toggle
- Export data option
- Browser-based persistence using localStorage
- Responsive layout for desktop, tablet and mobile screens

## Run locally

1. Clone or download this repository.
2. Open `incomtra/income-and-expense-tracker/index.html` in a modern browser.
3. Create a demo account using the sign-up form.
4. Add transactions, categories and savings goals from the dashboard.

The project loads Font Awesome, Google Fonts, Tailwind CSS and Chart.js from CDNs, so an internet connection is needed for those external assets.

## Data storage and security

This is a front-end learning/demo project. Finance data and demo account details are stored in the browser's `localStorage`. They are specific to the same browser and device and are not synced to a server.

**Do not use real passwords or sensitive financial information in this demo.** The current sign-up/login flow stores credentials in browser storage and is not secure authentication. The Google sign-in button is a placeholder, not a working OAuth integration. A production application needs a secure backend, proper password hashing, server-side authentication and database storage.

## Technology

- HTML5
- CSS3
- JavaScript (ES6+)
- localStorage
- Chart.js
- Font Awesome

## Notes

- Clearing browser storage can remove locally saved tracker data.
- Opening the project on another browser or device will not automatically transfer data.
- The app does not currently provide cloud backup or multi-user synchronization.
