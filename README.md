# perfi

Perfi is a personal finance app that I am building as a personal project to consolidate my full-stack development skills.
The app leverage the service provided by [Plaid](https://plaid.com/) to connect to financial institutions and retrieve financial data.
A list of implmented and planned features can be found below.

Demo version of the app can be found here: [https://perfi-app.herokuapp.com/](https://perfi-app.herokuapp.com/).

## Repositories:

The code for the app has been split across two repositories one for the front-end and one for the back-end.

- [Front-end](https://github.com/Mirthis/perfi-frontend)
- [Back-end](https://github.com/Mirthis/perfi-backend)

## Features

### Implemented

- Email/password authentication
- Connet to financial institutions and retrieve accounts (UK only for now)
- Retrieve accounts and display basic stats (balance, recent spending)
- Retrieve transactions for each account and assign them to pre-defined categories
- List transactions by category, month, account
- Display aggragated view of spending data using charts
- Exclude/include individual transactions from spending view
- Exclude/include all transactions in a specific category from spending view
- Assign transaction to a different category
- Assign similar transactions to a different category (based on name and merchant)
- Update category assignment algorithm based on user choices
- Create user defined
- Force account refresh (generally not needed)
- Change account permissions (renew, add accounts, remove accounts)

### Planned

- Add Google, Twitter, Facebook authentication
- Basic user profile and settings page
- Add notes to transactions
- Add buget tracking
- Testing suite
- Edit visibility of default category (hide/show, exclude/include transactions)

## Tech Stack

### Back-end

Typescript, Express, Passport, Postgresql, Sequelize

### Front-end

Typescript, React, Redux Toolkit, Material UI, Recharts
