# 🏏 T20 Cricket World Cup Data Analysis

## 📌 Project Overview
This project analyzes **T20 Cricket World Cup** data using **Python (Pandas)** and **Power BI** to generate insights about player and team performance.  
It follows a complete **data analytics pipeline** from raw JSON files to an interactive BI dashboard.

---

## 🎯 Objective
To convert raw cricket match and player data into structured datasets and meaningful visual insights that help answer:
- Who are the top-performing batsmen and bowlers?
- How did each team perform across matches?
- Which players had the highest impact on match outcomes?

---

## 📂 Project Structure
t20-world-cup-analysis/

├── data/

│ ├── raw/ # Original JSON data

│ └── processed/ # Cleaned & structured CSV tables

├── notebooks/ # Python data preprocessing

├── powerbi/ # Power BI dashboard

└── screenshots

└── README.md



---

## 📊 Dataset Description

### Raw Data (JSON)
- Batting summaries  
- Bowling summaries  
- Match results  
- Player information  

### Processed Data (CSV)
The raw data was transformed into a **star schema** for analytics:
- `fact_batting_summary.csv`
- `fact_bowling_summary.csv`
- `dim_players.csv`
- `dim_match_summary.csv`

This structure allows efficient analysis and visualization in Power BI.

---

## ⚙️ Data Processing
Data preprocessing was done using **Python (Pandas)** in Jupyter Notebook.

Key steps:
- Parsing mixed JSON and CSV formats  
- Cleaning missing and inconsistent values  
- Feature engineering (strike rate, economy, etc.)  
- Creating fact and dimension tables  
- Exporting final analytical datasets  

---

## 📈 Power BI Dashboard
The Power BI dashboard provides:
- Top run scorers  
- Best bowlers  
- Team-wise performance  
- Player impact analysis  

Open the `.pbix` file in **Power BI Desktop** to explore the interactive visuals.

---

## 🛠 Tools & Technologies
- Python (Pandas, Jupyter Notebook)  
- Power BI  
- JSON & CSV  
- Git & GitHub  

---

## 💼 Skills Demonstrated
- Data cleaning & wrangling  
- Feature engineering  
- Data modeling (Star Schema)  
- Business-focused analytics  
- Dashboard design  
- Version control  

---

## 👩‍💻 Author
**Rohini R**  
Computer Science & Engineering Student  
