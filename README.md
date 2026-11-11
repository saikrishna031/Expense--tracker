# Project 03 — Expense Tracker

A personal finance tracker built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Add income and expenses with description, amount, category and date.
- Automatically calculates balance, total income and total expenses.
- Search transactions and filter by income/expense.
- Delete transactions with confirmation.
- Export transactions as CSV.
- Saves transactions and theme preference in Local Storage.
- Responsive desktop, tablet and mobile interface.
- Input validation and helpful empty states.

## Folder structure
```text
project-03-expense-tracker/
├── index.html
├── README.md
├── css/style.css
└── js/app.js
```

## Run locally
Extract the ZIP and open `index.html` in a browser. Alternatively open the folder in VS Code and use Live Server. No API key, backend or build step is needed.

## Important JavaScript functions
- `load()` reads saved transactions from Local Storage.
- `save()` stores the transaction list.
- `renderSummary()` calculates income, expenses and balance.
- `renderList()` searches, filters and displays transactions.
- The form submit handler validates data and creates a transaction.
- The CSV export handler creates a downloadable spreadsheet file.

## GitHub upload
Create a public repository named `expense-tracker` at https://github.com/. Extract this ZIP, open a terminal in the folder, then run:
```bash
git init
git add .
git commit -m "Build expense tracker with vanilla JavaScript"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/expense-tracker.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your GitHub username. Alternatively use GitHub's Add file → Upload files option.

## GitHub Pages
Repository → Settings → Pages → Deploy from a branch → select `main` and `/(root)` → Save. URL: `https://YOUR-USERNAME.github.io/expense-tracker/`.

## Vercel
Sign in at https://vercel.com/ with GitHub → Add New → Project → import the repository → choose Other → leave build command and output directory empty → Deploy.

## Privacy
Transactions are saved only in this browser's Local Storage. They are not uploaded to a server. Export CSV backups before clearing browser site data.
