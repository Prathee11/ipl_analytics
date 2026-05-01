# Analysis Notes & Key Findings

## Methodology

All analysis is performed client-side using JavaScript arrays embedded directly in each HTML page. No server or database is required. Data was pre-processed from the Kaggle IPL dataset and hard-coded for performance.

---

## Key Findings

### 1. Scoring Inflation (Page 1 & 4)
- Average runs per match grew from **286 (2009)** to **357 (2026)** — a **+71 run increase**
- The sharpest jump occurred between **2016–2019** (T20 batting revolution)
- 2020 (UAE bubble) showed a brief dip, likely due to slower pitches

### 2. Team Dominance (Page 2)
- **Mumbai Indians** has the highest sustained win rate across active franchises
- Teams that win the toss convert it to a match win at ~**52%** — barely better than chance
- The **field-first strategy** has become dominant post-2016: >60% of toss winners choose to field

### 3. Venue Dynamics (Page 3)
- **Wankhede Stadium (Mumbai)** and **M. Chinnaswamy Stadium (Bengaluru)** are the highest-scoring venues
- **Chepauk (Chennai)** has the highest thriller rate — pitches produce the most close finishes
- Neutral venues (UAE, South Africa) tend to produce lower-scoring, tighter matches

### 4. Strategic Trends (Page 4)
- The **bat-first advantage** has inverted: teams batting second now win more consistently
- Thriller matches (decided by ≤10 runs / last over) peaked in **2016 and 2023**
- Powerplay scoring has increased the most relative to death-overs scoring

---

## Limitations

- Data is pre-processed and hard-coded — not live/real-time
- Ball-by-ball data not included (only match-level aggregates)
- Player-level statistics are outside the current scope
- 2026 represents a partial season

---

## Potential Extensions

- [ ] Add player-level performance pages
- [ ] Integrate live data via Cricinfo/Cricbuzz API
- [ ] Add search/filter functionality across all pages
- [ ] Build a Python notebook for the underlying data processing
- [ ] Add mobile-optimised layout
