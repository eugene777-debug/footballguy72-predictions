# TheFootballGuy72 Prediction Tracker

A static dashboard tracking [TheFootballGuy72's](https://www.youtube.com/@TheFootballGuy72) Premier League 2026/27 season predictions against actual results.

## 📊 Current Stats (as of 2026-09-06)

- **Exact Scores**: 4/20 (20%)
- **Correct Results**: 11/20 (55%)
- **Season MAE**: 5.0 points
- **Matchweeks Tracked**: 2 (20 matches)

## 🎯 What's Inside

- **Season Predictions Table**: Pre-season predicted final positions vs. current standings
- **Matchweek-by-Matchweek Results**: Detailed prediction accuracy for each match
- **Summary Statistics**: Overall prediction performance metrics
- **Dark Football Aesthetic**: Polished, mobile-friendly design

## 🚀 Usage

### View Locally

1. Clone this repository
2. Open `index.html` in your browser
3. No build step required - pure HTML/CSS/JS

### Deploy with GitHub Pages

1. Go to your repository **Settings**
2. Navigate to **Pages** (under "Code and automation")
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Your dashboard will be live at:
   
   **https://eugene777-debug.github.io/footballguy72-predictions/**

## 📁 Structure

```
.
├── index.html                  # Self-contained dashboard (JSON inlined)
├── data/
│   └── dashboard_data.json     # Source prediction data
└── README.md                   # This file
```

## 📈 Data Sources

- **Predictions**: TheFootballGuy72 YouTube channel
- **Actual Results**: [Transfermarkt Premier League Table](https://www.transfermarkt.com/premier-league/tabelle/wettbewerb/GB1/saison_id/2026)

## 🔄 Updating Data

To add new matchweek results:

1. Edit `data/dashboard_data.json` with new matches
2. Update the same JSON in the `<script id="data">` tag inside `index.html`
3. Commit and push - GitHub Pages will auto-deploy

---

Built with ⚽ for TheFootballGuy72 | [Visit the YouTube Channel](https://www.youtube.com/@TheFootballGuy72)
