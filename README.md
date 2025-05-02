
# 🏆 Premier League Power BI Report

An interactive Power BI report analyzing historical English Premier League data. Built from a cleaned dataset containing match results, team statistics, and performance metrics, this report provides insights into team form, standings, and trends across multiple seasons.

---

## 📊 Data Overview

This Power BI report is built using historical English Premier League match data sourced from [football-data.co.uk](http://football-data.co.uk/). The dataset includes detailed match statistics across multiple seasons and covers various performance metrics for both home and away teams.

### ✅ Key Data Fields:

- **Match Info:** Date, Season, Division, Matchweek, Referee  
- **Teams:** Home Team, Away Team  
- **Scores:** Full-Time Home Goals (FTHG), Full-Time Away Goals (FTAG), Result (Win/Draw/Loss)  
- **Half-Time Data:** Half-Time Home Goals, Half-Time Away Goals, Half-Time Result  
- **Match Statistics:**
  - Shots, Shots on Target  
  - Fouls, Corners, Yellow/Red Cards  
  - xG (expected goals), if available  
- **Betting Odds (Optional):** Odds for home win, draw, and away win from multiple bookmakers  
- **Derived Metrics:** Team performance stats like Wins, Draws, Losses, Points, Goal Difference, etc.

### 🗂 Data Structure:

- A single, cleaned table named `premierleague_data`
- Measures stored in a dedicated table called `Base Measure` for improved performance and maintainability

---

## 📁 Project Structure

New_Premier_PowerBI/
│
├── 📂 data/
│ └── clean_premier_league_data.csv # Final dataset used in the report (optional upload)
│
├── 📂 report/
│ └── New_Premier.pbix # Main Power BI report file
│
├── 📂 docs/
│ └── data_overview.md # Detailed explanation of data fields and structure
│ └── metrics_explained.md # Optional: Describe each DAX measure
│
├── 📂 assets/
│ └── preview.png # Optional: Screenshots of report visuals
│
├── .gitignore # Git ignore file (can exclude .pbix if repo is public)
├── README.md # Project overview and setup instructions


---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `New_Premier.pbix` in Power BI Desktop.
3. Explore the report pages, visuals, and DAX measures.
4. (Optional) Replace the dataset with updated seasons from [football-data.co.uk](http://football-data.co.uk/).

---

## 🛠 Tools Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel / CSV** for data prep
- **GitHub** for version control and collaboration

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and share.

---

## 🙌 Acknowledgments

- [football-data.co.uk](http://football-data.co.uk/) for making historical Premier League data freely available
- The Power BI community for resources and inspiration
