# Viceroy-expenses
Keeps track of 528 apt expenses to split with Libby.

- [`expenses.csv`](./expenses.csv) — append-only ledger of monthly Xfinity, Xcel Energy, and
  Domuso (rent) charges: `date,vendor,amount,billing_period,notes`.
- [`summary.md`](./summary.md) — latest cycle's totals and the 50/50 split.

A scheduled monthly task scans Gmail on the 8th, tallies these three vendors' latest
charges, appends them to the ledger, updates the summary, commits, and emails both
roommates the totals and split.
