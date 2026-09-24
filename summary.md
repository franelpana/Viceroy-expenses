# Expense Summary

Running ledger of shared apartment costs for Viceroy Observatory Park unit 1911-528, split 50/50 between Francisco and Libby.

Full transaction history: [`expenses.csv`](./expenses.csv).

## Latest cycle: September 2026

| Vendor | Amount |
|---|---|
| Domuso (rent) | $2,554.63 |
| Xfinity | $41.38 |
| Xcel Energy | $124.19 |
| **Total** | **$2,720.20** |

**Each person's share (50/50): $1,360.10**

## How this updates

A scheduled monthly task scans Gmail on the 8th of each month for the latest bill/payment
confirmation from Xfinity, Xcel Energy, and Domuso, appends a row per vendor to
`expenses.csv`, regenerates this summary, and emails the totals and split to both
franelpana@gmail.com and libskee@gmail.com.
