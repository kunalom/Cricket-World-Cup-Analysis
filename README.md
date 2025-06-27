# 🏆 Cricket World Cup 2023 Analysis – Power BI Dashboard

## 📌 Project Overview

This project presents an in-depth performance analysis of players who participated in the **2023 50-over Cricket World Cup**, using interactive dashboards built in **Power BI**. Data was scraped from **ESPN Cricinfo**, processed using **Python (NumPy, Pandas)**, and transformed via **Power Query** in Power BI.

Unlike traditional roles, this analysis breaks players into **five performance-based categories**:
- 🧢 Openers
- 🧱 Middle Order
- 💥 Finishers
- ⚔️ All-Rounders
- 🎯 Bowlers

The goal is to **compare and rank players within each role** using multiple key metrics, and finally construct a **data-driven Final XI** squad.

---

## 🔧 Tools & Technologies

- **Python:** Web scraping (BeautifulSoup/Requests), data cleaning (NumPy, Pandas)
- **Power BI:** Data modeling, interactive visualizations, DAX expressions
- **Power Query:** Data transformation and preprocessing
- **ESPN Cricinfo:** Source of player-level statistics

---

## 📊 Project Workflow

### 1. **Data Collection**
- Scraped detailed stats for each participating player from ESPN Cricinfo.
- Gathered metrics like runs, strike rate, batting average, bowling average, economy rate, bowling strike rate, etc.

### 2. **Data Cleaning (Python)**
- Used **NumPy and Pandas** to clean and structure the raw data.
- Removed inconsistencies, handled missing values, and merged multiple tables into a single dataset.

### 3. **Data Preprocessing (Power Query)**
- Further filtered and reshaped the dataset inside Power BI using Power Query.
- Created role-based splits: **Opener, Middle Order, Finisher, All-Rounder, Bowler**.

### 4. **Visualization & Analysis (Power BI)**
- **Batsmen Section:**
  - Compared players based on:
    - ✅ Batting Average only
    - ✅ Strike Rate only
    - ✅ Combined Score (Average + Strike Rate)
  - Role-wise filtering: Opener, Middle Order, Finisher

- **Bowlers Section:**
  - Compared players based on:
    - ✅ Bowling Average
    - ✅ Economy Rate
    - ✅ Strike Rate
    - ✅ Combined Bowling Performance Score

- **All-Rounders Section:**
  - Evaluated on balance between both batting and bowling metrics.

- **Final XI:**
  - Based on statistical performance across all roles, selected a balanced and impactful **Final 11** team.

---
## Images:
![{602CA79A-D33C-4F60-9A4E-D24CD1A17008}](https://github.com/user-attachments/assets/e3ebeca5-dcb9-4adb-bac0-4d304e2fe380)
![{8AC1E92D-8F87-46A8-BEAA-2F1B4E1305D6}](https://github.com/user-attachments/assets/62d6f9e6-971d-416a-919c-f031a2abc08e)

 
---
## 📈 Key Features

- 🧠 **Role-based segmentation** of players for more meaningful comparisons
- 📊 **Multiple metric filters** (Average, Strike Rate, Economy) for deeper insights
- 🔍 **Individual player comparisons** within each category
- 🧪 **Custom scoring logic** to fairly rank and compare players
- 🏅 **Final XI recommendation** based purely on performance data

---

---

## 🧭 Future Enhancements

- Add team-wise filtering and comparisons
- Add match-wise breakdown and performance trends
- Add predictive modeling (e.g., performance forecasting)
- Use APIs for real-time data instead of static scraping

---

## 🙌 Acknowledgements

- Data Source: [ESPN Cricinfo](https://www.espncricinfo.com)
- Tools: Python, Power BI, Power Query, Pandas, NumPy

---

## 📬 Contact

**Kunal Pathak**  
Email: kunalpathak@gmail.com 

