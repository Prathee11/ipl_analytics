# Data Sources

## Primary Dataset

| Field | Details |
|---|---|
| **Name** | IPL Complete Dataset (2008–2026) |
| **Source** | [Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020) |
| **Coverage** | Seasons 2009–2026 (995 matches) |
| **License** | CC0 – Public Domain |

## Key Data Fields Used

| Column | Type | Description |
|---|---|---|
| `season` | int | IPL season year |
| `team1` / `team2` | string | Competing teams |
| `winner` | string | Winning team |
| `venue` | string | Match stadium |
| `toss_winner` | string | Toss-winning team |
| `toss_decision` | string | `bat` or `field` |
| `result_margin` | int | Winning margin (runs/wickets) |
| `city` | string | Host city |

## Derived Metrics

These metrics are computed directly in JavaScript within each dashboard page:

- **Avg Runs / Match** — total runs ÷ total matches per season
- **Thriller Matches** — matches decided by ≤ 10 runs or in the final over
- **Win Rate** — wins ÷ total matches for each team
- **Toss Conversion Rate** — toss wins that converted to match wins ÷ total toss wins
- **Venue Impact Score** — composite of avg runs, thriller rate, and match frequency

## Data Notes

- Season 2010 is excluded from the dataset (IPL was held in South Africa, incomplete records)
- 2026 data reflects partial season (24 matches as of dataset freeze)
- Team name aliases are normalised (e.g. "Delhi Daredevils" = "Delhi Capitals")
- "Rising Pune Supergiants" and other defunct franchises are included in historical analysis
