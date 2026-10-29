# Godavari Bank: Online Banking Simulation

Static demo built with HTML, CSS, Bootstrap 5 and plain JavaScript. No real money or real banking data.

Pages: `index.html` (login), `signup.html`, `dashboard.html`, `transfer.html`, `transactions.html`.

## How it works
- Sign up creates an account with a 12-digit account number and ₹10,000 of demo money.
- Accounts, balances and transactions are saved in the browser's localStorage, so there is no server or database.
- Transfers to another Godavari Bank account number credit that account too. Other account numbers are treated as outside banks.
- Data is per browser. To reset, clear this site's data in the browser.

## Deploy
1. Push this folder to a GitHub repo.
2. On vercel.com, choose "Add New Project", import the repo, and click Deploy. No build command is needed.
