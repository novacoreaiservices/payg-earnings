# PAYG Earnings

Hourly pay-as-you-go (PAYG) earnings for Novacore's three Sogni workers
(NFT #462 on novacore-x870, #463 on novacore-x570, #478 on adam5070),
derived from the hourly income log in
[novacoreaiservices/sogni-income-history](https://github.com/novacoreaiservices/sogni-income-history).

PAYG figures are the workers' share of per-job payments. Subscription
(Unlimited Spark) earnings live in the income-history repo, not here.

## Files

- `hourly-payg-earnings.csv` — one row per hourly collection, Sep 29, 2026 onward.

| Column | Meaning |
| --- | --- |
| timestamp_utc / timestamp_toronto | When the hour was collected |
| day_label | Sogni accounting day (resets midnight UTC, 7pm Toronto) |
| payg_day_usd / payg_day_cad | PAYG earned so far in the accounting day |
| payg_hour_usd / payg_hour_cad | PAYG earned in that hour (change vs the previous row) |
| sub_day_usd / total_day_usd | Subscription and combined day-so-far, for context |

## Notes

- Nov 5–6, 2026: all three workers ran PAYG-only for a 24h experiment
  (switched 10:15pm Nov 5, back 10:15pm Nov 6). PAYG figures in that
  window reflect PAYG-only mode; outside it, subscription is the main
  stream and PAYG is small by design.
- Snapshot as of Nov 6, 2026 6:47pm EST. Updates are manual for now.
