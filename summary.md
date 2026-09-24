# Expense Summary

Running ledger of shared apartment costs for Viceroy Observatory Park unit 1911-528, split 50/50 between Francisco and Libby.

Full transaction history: [`expenses.csv`](./expenses.csv).

## August 2026 (move-in month — rent-free)

| Vendor | Amount |
|---|---|
| Xfinity | $41.38 |
| Xcel Energy | $132.26 |
| Domuso (rent) | $0.00 — no rent charge landed in August (free move-in month) |
| **Total** | **$173.64** |

**Each person's share (50/50): $86.82**

> Note: a separate $1,016.00 Domuso payment was made 2026-07-31 (pre-move-in/pre-August). This
> has already been paid and split between Francisco and Libby outside of this ledger, so it's
> excluded from the totals above and not tracked further here.

## Latest cycle: September 2026

| Vendor | Amount |
|---|---|
| Domuso (rent) | $2,554.63 |
| Xfinity | $41.38 |
| Xcel Energy | $124.19 |
| **Total** | **$2,720.20** |

**Each person's share (50/50): $1,360.10**

## Running total (August + September 2026)

- **Combined total:** $2,893.84
- **Each person's share (50/50):** $1,446.92

## How this updates

A scheduled monthly task scans Gmail on the 8th of each month for the latest bill/payment
confirmation from Xfinity, Xcel Energy, and Domuso, appends a row per vendor to
`expenses.csv`, regenerates this summary, and emails the totals and split to both
franelpana@gmail.com and libskee@gmail.com.
