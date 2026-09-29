# Smart Khatabook

## Project overview

A digital khata-book interface for managing customer accounts, credit, payments, collections, purchases, transactions, reports, and business settings.

## What it contains

- React and Vite frontend
- Registration and login screens
- Dashboard with shared sidebar navigation
- Customer and add-customer screens
- Credit, payment, shopping, and collection workflows
- Transaction history and reports
- Context, routes, services, and reusable components
- A nested `khatabook2/` directory whose relationship to the root app should be documented

## Current status

The visible root application provides the frontend product structure. A production backend, durable financial/customer data store, authentication/session security, audit trail, backup/restore behavior, and automated tests are not established by the previous README.

## Local development

```bash
npm install
npm run dev
```

## Important boundary

Do not use the application for real financial records until data integrity, access control, transaction correctness, backups, and recovery have been verified.

## Recommended next work

Clarify the purpose of `khatabook2/`, document the complete architecture, implement or connect secure persistence, and add tests for balances, payments, collections, permissions, and reporting totals.
