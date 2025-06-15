# Agri Data Analysis Project 🌾📊

This project focuses on analyzing Indian agricultural data using **Exploratory Data Analysis (EDA)** in Python and **SQL-based querying**, with results visualized in **Power BI**. The goal is to uncover trends, production patterns, and insights across multiple crops over several decades at the state and district levels.

---

## 📁 Project Structure
📂 agri-project/
├── eda.ipynb # Python notebook for EDA
├── sql_analyis.ipynb # SQL queries for deeper insights
├── AgriDashboard.pbix # Power BI dashboard with visualizations
├── agridata.csv # Dataset containing crop production, area, yield, etc.
└── README.md # Project documentation

 
---

## 📌 Objectives

- Analyze crop production trends (e.g., rice, wheat, oilseeds, maize).
- Identify top producing states and districts.
- Visualize changes in crop yield, production, and cultivated area over time.
- Use correlation and comparative analysis to discover patterns.
- Present data insights interactively using Power BI.

---

## 🔍 Exploratory Data Analysis (EDA)

Performed using Python libraries such as:
- `pandas`, `matplotlib`, `seaborn`, and `plotly`

Key EDA insights:
- Top 7 states for rice and wheat production
- Oilseed and sunflower production by states
- 50-year trend of sugarcane production
- Comparative analysis of rice vs wheat production
- Correlation heatmaps between area and production

---

## 🧮 SQL-Based Analysis

Executed with SQL queries to:
- Aggregate crop data at state/district level
- Identify year-over-year (YoY) growth in yield/production
- Calculate 5-year growth rates
- Filter and rank states based on specific crop metrics

---

## 📊 Power BI Dashboard

The Power BI `.pbix` file includes:
- **Page 1:** EDA-based visuals (bar charts, line plots, pie charts, scatter plots, heatmaps)
- **Page 2:** SQL-driven insights (tables, top-N filters, YoY comparisons)
- Interactive filters by year, crop, and state
- District-wise correlation heatmaps for selected crops

---

## 📦 Dataset

- Source: [`agridata.csv`]  
- Contains agricultural statistics from 1966 to 2017  
- Features include: `Year`, `State`, `District`, crop-wise `Area`, `Production`, and `Yield`

---


