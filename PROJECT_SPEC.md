# Project Specifications -- Django Ledger

A web-based double entry accounting system.

## Design Specification

### Phase I
  - allow users to sign-up for a user account.
  - each user can have multiple companies/accounts.
  - database will have user editable chart of account for each company/account.
  - each company/account will have a chart of accounts and a general ledger.

### Phase II
  - editable general ledger entries following double entry standards.
  - display general ledger and per account listings.

### Phase III
  - produce balance sheet and profit/loss statements.


## Technical Specification
  - use sqlite database, with the following per user account:
    - company/account (multiple)
    - chart of accounts (per company/account)
    - general ledger (per company/account)
  - django based web app.
  - bootstrap 5 for CSS styling.
  - use TDD.
  - deploy live via PythonAnyWhere.
