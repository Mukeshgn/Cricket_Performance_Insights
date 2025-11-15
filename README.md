# 🏏 Cricket Performance Insights — Data Analytics Project

> A comprehensive cricket analytics project using **Python (Pandas, Matplotlib)** and **Power BI** to visualize player performance, match statistics, and identify the **Best Playing XI** through data-driven insights.

---

## 📘 Project Overview

This project analyzes real-world cricket performance data to identify top-performing players, understand match trends, and evaluate batting and bowling efficiency.  
It combines **Python for data preprocessing and visualization** with **Power BI dashboards** for interactive insights and dynamic team selection.

> 📝 Note: All data is sourced and processed for educational and analytical demonstration purposes.

---

## 🧩 Project Workflow

| Phase | Description |
|--------|--------------|
| **1. Data Collection** | Extracted match and player data from **ESPNcricinfo** (JSON format). |
| **2. Data Preprocessing** | Used **Pandas** to clean, impute missing values, remove outliers, and normalize data. |
| **3. Exploratory Data Analysis (EDA)** | Analyzed batting and bowling trends using descriptive statistics and visual plots. |
| **4. Visualization (Matplotlib)** | Generated bar charts, scatter plots, histograms, and pie charts to highlight key patterns. |
| **5. Dashboarding (Power BI)** | Built interactive dashboards with filters for team comparison and dynamic Best XI selection. |
| **6. Reporting** | Compiled a full report and presentation summarizing insights and recommendations. |

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|----------|
| **Python (Pandas, Matplotlib)** | Data preprocessing, cleaning, and visualization |
| **Jupyter Notebook** | Interactive environment for data analysis |
| **Power BI** | Interactive dashboards and data storytelling |
| **Excel** | Data validation and manual cleaning |
| **Git & GitHub** | Version control and project showcase |

---

## 🧱 Dataset Summary

- **Source:** ESPNcricinfo (JSON → CSV format)
- **Type:** Player-level match and innings data
- **Key Features:**
  - Player Name, Team, Role (Batsman/Bowler)
  - Matches Played, Runs, Wickets, Strike Rate, Economy
  - Venue, Match Type, Opposition
- **Preprocessing Steps:**
  - Missing values handled via imputation  
  - Outliers removed (based on performance metrics)  
  - Normalized strike rate and economy distributions  

---

## 🎯 Objectives

1. Identify **top-performing players** (batting & bowling).  
2. Handle **missing values and outliers** for clean analysis.  
3. Understand **match and venue trends**.  
4. Select **Best Playing XI** based on metrics.  
5. Visualize results through **interactive dashboards**.  

---

## 💻 Sample Python Scripts

```python
# 🏏 Top 5 Run Scorers
top_scorers = df.groupby('Player')['Runs'].sum().sort_values(ascending=False).head(5)
top_scorers.plot(kind='bar', color='crimson', title='Top 5 Run Scorers')

# 🎯 Wickets Distribution
plt.hist(df['Wickets'], bins=10, color='skyblue')
plt.title('Distribution of Wickets')
plt.xlabel('Wickets Taken')
plt.ylabel('Frequency')
plt.show()
```
---

## 🖼️ Visual Insights
📊 Power BI Dashboard

The Power BI dashboard visualizes:
Matches won by each team (Bar Chart)
Wins by ground (Pie Chart)
Wins over days (Scatter Chart)
Top run-scorers and wicket-takers
Highest strike rates and economy rates
Dynamic Best Playing XI selection

---

# 🧠 Key Insights

Top Run-Scorers: Consistent players with strike rates > 130.
Bowling Trends: Fast bowlers dominate powerplays; spinners control middle overs.
Match Insights: Most wins recorded on neutral venues.
Venue Analysis: Certain grounds favor batsmen based on pitch data.
Best XI Selection: Data-backed combination of openers, anchors, finishers, all-rounders, and bowlers.

---

## 💡 Business/Analytical Value

Enables data-driven player selection for teams and tournaments.

Provides comparative analysis for batting and bowling units.
Helps coaches, selectors, and analysts make informed tactical decisions.
Demonstrates EDA + BI integration for sports analytics.

---

## 📄 Documentation
File	Description
📊 Final Report — Cricket Performance Insights
	Full project documentation including visualizations and outcomes
🧾 Project Synopsis
	Structured summary outlining objectives, scope, and methodology
🎥 Presentation — Cricket Performance Insights
	PowerPoint presentation summarizing results and dashboards

---

## 🧾 Conclusion

This project demonstrates how Python and Power BI can complement each other in sports analytics.
By leveraging data preprocessing, visual storytelling, and dashboard interactivity, the analysis provides actionable insights into player performance and strategic decision-making in cricket.

---

## ⚠️ Disclaimer

All data and visualizations are created for educational and portfolio purposes.
They do not represent any official cricket organization or player database.

---

## 👨‍💻 Author

Mukesh Gopi Nandh
📧 mukeshudatha7@gmail.com

---

## 🌐 Connect with Me:

🌐 Connect with Me:

<p align="left"> 
  <a href="https://github.com/Mukeshgn" target="_blank"> 
    <img src="https://img.shields.io/badge/GitHub-Mukeshgn-181717?style=for-the-badge&logo=github" alt="GitHub"/> 
  </a> 
  <a href="https://www.linkedin.com/in/mukesh-gopi-nandh" target="_blank"> 
    <img src="https://img.shields.io/badge/LinkedIn-Mukesh%20Gopi%20Nandh-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"/> 
  </a>
  <a href="https://mukeshgn.github.io/mukesh_portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-mukeshgn.github.io-8A2BE2?style=for-the-badge&logo=google-chrome" alt="Portfolio"/>
  </a>
</p>

