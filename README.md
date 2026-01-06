Below is a **README template** for your **football-ai-colab** project in **both English and Vietnamese**. You can copy this into your repository’s `README.md` and edit names/descriptions as needed.

---

## 📌 **README (English)**

# Football AI Colab

Football AI Colab is a Google Colab-based project for exploring football (soccer) statistics and analytics using publicly available datasets. This project includes data processing notebooks and stat comparison insights for players and matches.

---

## 📁 **Contents**

The repository contains:

* **Final_players_stats.csv** – Player and team rankings with metrics such as attack and defense values. Used in `ranking_players.ipynb`.
* **players_data_light-2024_2025.csv** – Player statistical data from the 2024/2025 season. Used in `Player_stat.ipynb`.
* **lineups.csv** – Match lineup data showing which players participated in each game and related summary stats.
* **Notebooks** – Jupyter Notebooks for processing and analyzing the datasets.

---

## 🚀 **Features**

✔ Load and explore football statistics.
✔ Compare players and teams by performance metrics.
✔ Generate visualizations and insights in Google Colab.
✔ Easy to modify and extend for your own analysis.

---

## 🧠 **Getting Started**

### Prerequisites

To use this project, you just need:

* A Google account
* Access to **Google Colab**

No special local installation required.

---

## 📌 **Usage**

1. Open the repository in your browser.
2. Click the notebook you want to run (e.g., `ranking_players.ipynb`).
3. Press **Open in Colab** (if linked) or upload it to your Google Drive.
4. Run the cells step by step to load data and see analysis results.

---

## 📊 Data Description (English)
source: https://www.kaggle.com/datasets/excel4soccer/espn-soccer-data/data 
### 1. `Final_players_stats.csv`

This file contains **ranking scores and performance points** for both **teams and individual players**.

* The **attack and defense scores** are **experimental** and **not ground-truth labels**.
* The **weights used to compute scores are referenced from online football analytics sources** and are meant **for exploration and comparison only**.
* Players are **matched with the matches they participated in**, allowing aggregated evaluation across games.
* This file is generated and analyzed in **`ranking_players.ipynb`**.

**Main purpose:**
To experiment with player/team ranking based on weighted performance metrics.

---

### 2. `players_data_light-2024_2025.csv`

This dataset contains **detailed statistical performance data of individual players** for the **2024–2025 season**.

* Focuses purely on **player statistics**
* No ranking or scoring system applied
* Used for **exploratory data analysis (EDA)** and stat comparison

Analyzed in **`Player_stat.ipynb`**.

---

### 3. `lineups.csv`

This file describes **which players participated in which matches**.

* Contains **match participation data**
* Includes **season-level aggregated statistics** for each player
* **Does NOT include ranking or scoring points**

**Main purpose:**
To link players with matches and support match-level aggregation.

---

## 🧾 Feature Explanation

| Column                | Description                                 |
| --------------------- | ------------------------------------------- |
| Player                | Player name                                 |
| Nation                | Player nationality (e.g., POR, ENG, FRA)    |
| Squad                 | Club the player is playing for              |
| Comp                  | Competition / League (e.g., Premier League) |
| Age                   | Player age (calculated per season)          |
| MP (Matches Played)   | Number of matches played                    |
| Min                   | Total minutes played                        |
| 90s                   | Matches equivalent to 90 minutes (Min / 90) |
| Goals                 | Total goals scored                          |
| Assists               | Total assists                               |
| G+A                   | Goals + Assists                             |
| Shots                 | Total shots attempted                       |
| Shots_on_Target       | Shots on target                             |
| xG (Expected Goals)   | Expected goals                              |
| xA (Expected Assists) | Expected assists                            |
| Goals_per_90          | Goals per 90 minutes                        |
| Assists_per_90        | Assists per 90 minutes                      |
| G+A_per_90            | (Goals + Assists) per 90 minutes            |
| Passes_Attempted      | Total passes attempted                      |
| Passes_Completed      | Accurate passes                             |
| Pass_Accuracy         | Pass accuracy (%)                           |
| Tackles               | Successful tackles                          |
| Interceptions         | Interceptions                               |
| Blocks                | Blocks                                      |
| Clearances            | Clearances                                  |

---
---

## 📌 **Structure**

```
football-ai-colab/
├── Final_players_stats.csv
├── players_data_light-2024_2025.csv
├── lineups.csv
├── ranking_players.ipynb
├── Player_stat.ipynb
├── README.md
```

---

## 📝 **Contribution**

Feel free to fork this project and contribute your improvements, whether it’s more analysis, new data visualizations, or machine learning models for football analytics.

---

## 📜 **License**

This repository has no specified license — add one if you want to define reuse permissions.

---

## 📞 **Contact**

Created by the **hoangthanh300405-ops** team.
Thanks to all contributors!

---

