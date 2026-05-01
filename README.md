<div align="center">

<!-- ANIMATED BANNER -->
<img src="assets/screenshots/banner.png" alt="IPL Analytics Dashboard Banner" width="100%"/>

<br/>

# 🏏 IPL Analytics Dashboard

### _16 Seasons · 995 Matches · 17 Teams · One Dashboard_

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Dashboard-ff6b35?style=for-the-badge&labelColor=060f2a)](https://YOUR_USERNAME.github.io/ipl-analytics/)
[![GitHub Stars](https://img.shields.io/github/stars/YOUR_USERNAME/ipl-analytics?style=for-the-badge&color=ffd700&labelColor=060f2a&logo=github)](https://github.com/YOUR_USERNAME/ipl-analytics/stargazers)
[![License](https://img.shields.io/badge/License-MIT-00d9ff?style=for-the-badge&labelColor=060f2a)](LICENSE)
[![Made With](https://img.shields.io/badge/Made_With-HTML_·_Plotly.js_·_Python-00ff88?style=for-the-badge&labelColor=060f2a)](#tech-stack)

<br/>

> A **data-driven, multi-page interactive analytics platform** for the Indian Premier League (2009–2026).  
> Built for analysts, fans, and anyone who wants to understand cricket through clean, beautiful data.

<br/>

</div>

---

## 📸 Dashboard Preview

| Page | Description |
|------|-------------|
| ![Executive Overview](assets/screenshots/page1-thumb.png) | **Executive Overview** — KPIs, season scoring evolution, match density heatmap |
| ![Team Performance](assets/screenshots/page2-thumb.png) | **Team Performance** — Win rates, head-to-head records, toss conversion |
| ![Venue Insights](assets/screenshots/page3-thumb.png) | **Venue & Match Insights** — Stadium scoring profiles, thriller rates |
| ![Trends](assets/screenshots/page4-thumb.png) | **Trends & Strategic Insights** — Temporal patterns, field-first vs bat-first |

> 📌 **Add your own screenshots** to `assets/screenshots/` using the filenames above.

---

## ✨ Features

- 🎯 **4 Dedicated Dashboard Pages** — each with a unique analytical focus
- 📊 **15+ Interactive Plotly Charts** — hover, zoom, filter, download
- ⚡ **Zero Backend Required** — pure HTML/CSS/JS, runs in any browser
- 🌓 **Cinematic Dark Theme** — deep navy + orange/gold IPL palette
- 📱 **Responsive Design** — works on desktop and tablet
- 🔢 **995 Matches Covered** — complete IPL dataset 2009–2026
- 🏆 **17 Teams Tracked** — active and disbanded franchises

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
Click **[Live Demo](https://YOUR_USERNAME.github.io/ipl-analytics/)** — no setup needed.

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

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5 / CSS3** | Structure & styling, no frameworks needed |
| **Plotly.js v2.35** | All interactive charts and visualizations |
| **Vanilla JavaScript** | Data processing, chart configuration |
| **Orbitron + Rajdhani + JetBrains Mono** | Custom Google Fonts |
| **CSS Custom Properties** | Design token system |
| **GitHub Pages** | Zero-cost static hosting |

---

## 📊 What's Inside Each Page

### Page 1 — Executive Overview
- **KPI Cards**: Total matches, avg runs/match, best win rate, thriller count
- **Season Scoring Evolution**: Line chart tracking avg runs 2009–2026
- **Match Volume Trend**: Bars showing matches per season
- **Summary Table**: Full dataset audit with key milestones

### Page 2 — Team Performance
- **Win Rate Leaderboard**: All 17 teams ranked
- **Head-to-Head Matrix**: Interactive rivalry grid
- **Toss Conversion Analysis**: Which teams capitalise on the toss
- **Consistency vs Peak Performance**: Scatter analysis

### Page 3 — Venue & Match Insights
- **Highest Scoring Venues**: Stadium-level run profiles
- **Thriller Rate Map**: % of close-finish matches by ground
- **Avg Runs by Venue**: Comparative bar breakdown
- **Venue Impact Score**: Composite stadium ranking

### Page 4 — Trends & Strategic Insights
- **Scoring Inflation Over Decades**: IPL run-rate evolution
- **Field-First vs Bat-First Win %**: Strategy shift analysis
- **Toss → Win Correlation**: Does the toss actually matter?
- **Season-wise Thriller Frequency**: When were the most nail-biters?

---

## 🔑 Key Findings

> These are the insights the dashboard was built to surface:

- 📈 **+71 runs** average per match since 2009 (286 → 357)
- 🏟️ Wankhede and Chinnaswamy produce the **highest scoring matches**
- 🎯 Toss-to-win conversion: ~**52%** across all seasons — marginal advantage
- ⚡ **Thriller matches** (decided by <10 runs or last over) peaked in 2016 & 2023
- 🏆 **Mumbai Indians** holds the highest multi-season win rate among active teams

---

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

**Made with ❤️ and a lot of cricket data**

⭐ Star this repo if you found it useful — it helps others discover it!

[![Follow](https://img.shields.io/github/followers/YOUR_USERNAME?style=social)](https://github.com/YOUR_USERNAME)

</div>
