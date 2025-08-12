# 🌍 Day 3 – CO₂ Emissions EDA & Visualization

## 📌 Project Overview
This project explores **global CO₂ emissions trends** from historical data across different countries and years.  
We analyze **global growth**, **top emitters**, **country comparisons**, and even **interactive maps** to better understand emission patterns.

**Dataset Example:**
- Country
- ISO Code
- Year
- Annual CO₂ emissions (in tonnes)

---

## 📊 Key Insights
- **Global emissions** have generally risen over the decades, with some dips during global crises.
- **Top emitters** are dominated by China, USA, and India in recent years.
- Growth patterns differ significantly between developed and developing nations.

---

## 📂 Folder Structure
Day3_EDA_Visualization/
│
├── Data/
│ └── co2_emissions.csv
│
├── Images/
│ ├── global_trend.png
│ ├── top_emitters.png
│ ├── usa_china_india_trend.png
│ ├── pakistan_growth_rate.png
│
├── co2_emissions_analysis.py
├── README.md
├── requirements.txt
└── .gitignore


---

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YourUsername/Day3_EDA_Visualization.git
cd Day3_EDA_Visualization
pip install -r requirements.txt
python co2_emissions_analysis.py

📦 Dependencies
pandas → Data manipulation

matplotlib & seaborn → Static visualizations

plotly → Interactive maps

numpy → Numerical operations

📈 Visualizations Included
Global CO₂ emissions trend over time

Top 10 CO₂ emitters in the latest year

Country-wise trends (USA, China, India)

Interactive choropleth map for any year

Yearly growth rate for a selected country

💡 Next Steps / Future Improvements
Add per capita emissions analysis

Include renewable energy adoption trends

Compare CO₂ emissions with GDP and population

✍ Author: Akhtar Abas
📅 Date: 2025-08-12