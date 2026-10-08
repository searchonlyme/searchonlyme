# SearchOnly — OnlyFans market data (daily)

Daily aggregate figures about the OnlyFans creator market, measured by
[SearchOnly](https://searchonly.me) from public profiles. One row per day,
appended automatically after each nightly report.

- **File:** [`market-daily.csv`](market-daily.csv)
- **Method:** https://searchonly.me/reports/methodology
- **Live reports and charts:** https://searchonly.me/reports
- **Cite:** see [`CITATION.cff`](../CITATION.cff); monthly versions are archived with a DOI on Zenodo.
- **Licence:** [CC BY 4.0](LICENSE) — free to use,
  share and adapt with attribution: *"Source: SearchOnly (searchonly.me)"*, with a link.

Aggregates only: no creator names, usernames or identifiers.

## Columns

| Column | Meaning |
|---|---|
| `date` | report day (UTC) |
| `profiles` | public creator profiles in the index |
| `live` | profiles still available on OnlyFans |
| `new_24h`, `new_7d` | profiles first seen in the last 24 hours / 7 days |
| `gone_7d` | profiles that disappeared in the last 7 days |
| `free_share` | share of creators free to follow (0–1) |
| `median_paid_usd`, `avg_paid_usd` | monthly price of paid subscriptions |
| `price_window` | the window of the price columns: `7d` = the last 7 days; `since_first` = since our first measurement (early rows) — don't compare across windows |
| `price_compared` | profiles whose price was compared in that window |
| `price_changed`, `price_raised`, `price_lowered` | of those: any change, increases, decreases |
| `went_free`, `went_paid` | paid → free, free → paid |

Figures are measured, never estimated; we do not estimate creators' earnings.
