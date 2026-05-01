<div align="center">

# 🏏 IPL Analytics Dashboard

<<<<<<< HEAD
An interactive, multi-page data analytics dashboard built to explore 16 seasons of Indian Premier League cricket (2009–2026). This project transforms raw match data into meaningful visual insights using Plotly.js, covering team performance, venue dynamics, scoring trends, and strategic patterns across 995 matches and 17 franchises.
=======
An interactive, multi-page data analytics dashboard built to explore 16 seasons of Indian Premier League cricket (2009–2026). This project transforms raw match data into meaningful visual insights, covering team performance, venue dynamics, scoring trends, and strategic patterns across 995 matches and 17 franchises.
>>>>>>> 855a066cfd926579ec90f42084145fbedbd1d63e


</div>

---

## Overview
The IPL Analytics Dashboard is a fully client-side web application — no backend, no database, no installation required. It runs entirely in the browser and is structured across four dedicated pages, each focusing on a distinct analytical dimension of IPL data. The project was built to demonstrate end-to-end data storytelling: from raw dataset to polished, interactive visualisation.

<<<<<<< HEAD
Page 1 — Executive Overview
A high-level summary of the entire dataset. Includes key performance indicators, season-by-season scoring evolution from 2009 to 2026, match volume trends, and a complete data audit table highlighting major milestones across IPL history.
Page 2 — Team Performance
A deep dive into franchise-level statistics. Covers win rates for all 17 teams, head-to-head rivalry records, toss conversion analysis, and consistency metrics that distinguish dominant teams from inconsistent ones.
Page 3 — Venue and Match Insights
A ground-by-ground breakdown of every IPL venue. Analyses average runs scored, thriller rates (matches decided in the final over or by fewer than 10 runs), venue impact scores, and how different stadiums influence match outcomes.
Page 4 — Trends and Strategic Insights
=======
## Page 1 — Executive Overview
A high-level summary of the entire dataset. Includes key performance indicators, season-by-season scoring evolution from 2009 to 2026, match volume trends, and a complete data audit table highlighting major milestones across IPL history.

## Page 2 — Team Performance
A deep dive into franchise-level statistics. Covers win rates for all 17 teams, head-to-head rivalry records, toss conversion analysis, and consistency metrics that distinguish dominant teams from inconsistent ones.

## Page 3 — Venue and Match Insights
A ground-by-ground breakdown of every IPL venue. Analyses average runs scored, thriller rates (matches decided in the final over or by fewer than 10 runs), venue impact scores, and how different stadiums influence match outcomes.

## Page 4 — Trends and Strategic Insights
>>>>>>> 855a066cfd926579ec90f42084145fbedbd1d63e
A temporal and tactical analysis of how the IPL has evolved. Tracks scoring inflation over 16 seasons, the strategic shift from bat-first to field-first decisions, toss-to-win correlation, and the frequency of high-pressure finishes over time.

---
## Key Findings
<div class="key-findings">

<<<<<<< HEAD
## Key Findings

Average runs per match increased by 71 runs between 2009 and 2026, rising from 286 to 357
Teams winning the toss convert it into a match win approximately 52% of the time, suggesting minimal tactical advantage
The field-first strategy has become the dominant choice post-2016, with over 60% of toss winners opting to chase
Wankhede Stadium (Mumbai) and M. Chinnaswamy Stadium (Bengaluru) consistently produce the highest-scoring matches
Thriller matches peaked in the 2016 and 2023 seasons
=======
  <p>📈 <b>Scoring Surge:</b> Average runs per match increased by 71 runs (from 286 in 2009 to 357 in 2026), highlighting a clear shift toward aggressive batting.</p>

  <p>🪙 <b>Toss Impact:</b> Teams convert toss wins into match victories only about 52% of the time, indicating minimal strategic advantage.</p>

  <p>🎯 <b>Chasing Trend:</b> Since 2016, the field-first strategy dominates, with 60%+ of captains opting to chase.</p>

  <p>🏟️ <b>High-Scoring Venues:</b> Wankhede Stadium and M. Chinnaswamy Stadium consistently produce high-scoring matches.</p>

  <p>🔥 <b>Thriller Peaks:</b> Close matches (thrillers) peaked during the 2016 and 2023 seasons, indicating periods of heightened competitiveness.</p>

</div>
>>>>>>> 855a066cfd926579ec90f42084145fbedbd1d63e
---

## 📁 Project Structure

```
ipl-analytics/
│
├── 📄 Page1_Executive_Overview.html   # KPIs · Season trends · Match heatmap
├── 📄 Page2_Team_Performance.html     # Win rates · Head-to-head · Toss stats
├── 📄 Page3_Venue_Insights.html       # Stadium profiles · Scoring maps
├── 📄 Page4_Trends_Insights.html      # Temporal trends · Strategy patterns
│
├── 📂 assets/
│   └── 📂 screenshots/               # Preview images for README
│
├── 📂 docs/
│   ├── DATA_SOURCES.md               # Dataset origin & structure
│   ├── DESIGN_SYSTEM.md              # Color palette, typography, components
│   └── ANALYSIS_NOTES.md            # Key findings & methodology
│
├── 📂 .github/
│   ├── 📂 workflows/
│   │   └── deploy.yml                # GitHub Pages auto-deploy
│   └── 📂 ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
│
├── 📄 index.html                     # Landing / navigation hub
├── 📄 LICENSE                        # MIT License
├── 📄 CONTRIBUTING.md                # How to contribute
└── 📄 README.md                      # You are here
```

---

## 🚀 Quick Start

### Option 1: View Live (Recommended)
Click **[Live Demo](https://Prathee11.github.io/ipl-analytics/)** — no setup needed.

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/ipl-analytics.git
cd ipl-analytics

# Open in browser (any of these work)
open index.html                        # macOS
start index.html                       # Windows
xdg-open index.html                   # Linux

# Or serve locally for best performance
npx serve .                            # Node.js
python -m http.server 8000            # Python
```
Then visit `http://localhost:8000`


## 🗂️ Data Sources

| Dataset | Coverage | Source |
|---|---|---|
| Match Results | 2009–2026, 995 matches | [Kaggle – IPL Complete Dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020) |
| Team Records | 17 franchises | Derived from match data |
| Venue Data | All IPL grounds | Derived from match data |

> Full details in [`docs/DATA_SOURCES.md`](docs/DATA_SOURCES.md)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m 'Add: descriptive message'`
4. Push to branch: `git push origin feature/your-feature`
5. Open a Pull Request

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for detailed guidelines.

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

<div align="center">

**Made with ❤️  **

⭐ Star this repo if you found it useful — it helps others discover it!



</div>
