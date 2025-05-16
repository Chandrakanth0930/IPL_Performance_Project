
# IPL Data Analysis Project

## 📁 Project Overview

This project leverages IPL match data to generate interactive visualizations and extract actionable insights. It uses a cleaned dataset of IPL matches and a Power BI report (`.pbix`) to present the findings.

---

## 📦 Contents

- **`ipl_matches_cleaned.csv`**: Cleaned IPL match dataset including teams, venues, results, and other match-level details.
- **`ipl.pbix`**: Power BI report containing visual dashboards created from the CSV data.

---

## 📊 Dataset Description: `ipl_matches_cleaned.csv`

| Column Name          | Description                                             |
|----------------------|---------------------------------------------------------|
| id                   | Unique match identifier                                 |
| city                 | City where the match was played                         |
| date                 | Date of the match                                       |
| player_of_match      | Best performer of the match                             |
| venue                | Stadium where the match took place                      |
| neutral_venue        | Whether the venue was neutral (1 = Yes, 0 = No)         |
| team1                | First team                                              |
| team2                | Second team                                             |
| toss_winner          | Team that won the toss                                  |
| toss_decision        | Decision taken after toss (bat/field)                   |
| winner               | Team that won the match                                 |
| result               | Result type (normal, tie, etc.)                         |
| result_margin        | Margin by which the match was won                       |
| eliminator           | Whether it was an eliminator match (Y/N)                |
| method               | Method of victory (e.g., DLS method)                    |
| umpire1              | First umpire                                            |
| umpire2              | Second umpire                                           |

---

## 📈 Report: `ipl.pbix`

This Power BI report includes:
- **Team performance** by season and overall
- **Toss impact analysis** on match outcomes
- **Top venues** and winning patterns
- **Player of the Match frequency**
- **Interactive filters** (year, venue, team)

---

## 🛠️ Tools Used

- **Power BI** for dashboarding and data visualization  
- **CSV/Excel** for data manipulation  
- **(Optional)** Python or Excel for initial data cleaning  

---

## 🚀 How to Use

1. Open the `ipl.pbix` file in Power BI Desktop.
2. Explore visualizations or apply filters to view custom insights.
3. To edit or extend data, update `ipl_matches_cleaned.csv` and refresh the Power BI model.

---

## 📌 Notes

- Ensure Power BI Desktop is installed to view the `.pbix` file.
- The CSV file must remain in the same structure if updates are made.
