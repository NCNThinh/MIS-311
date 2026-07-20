# MIS 311 - Exploratory Data Analysis: Global Tourism Trends

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on global tourism arrival statistics to evaluate post-pandemic recovery patterns and geographic market concentration. 

* **Dataset:** Most Visited Countries (Dataset #7)
* **Tools Used:** Python (Pandas, Matplotlib, Seaborn)

---

## 🧹 Data Cleaning & Preparation
* **Duplicate Detection:** Checked for duplicate records across the dataset; 0 duplicate rows were identified.
* **Missing Value Handling:** Original missing values (`NaN`) in international arrival metrics were identified and imputed using zero-fill (`df.fillna(0)`) to preserve sample size across 200+ countries without skewing comparative aggregations.

---

## 📊 Key Findings & Insights

### Insight 1: Market Concentration in Global Travel Destinations
![Top 10 Countries](top_10_countries.png)

> The descriptive statistics reveal a heavy concentration of global tourism demand within a few elite destinations, with France leading the global market at 100 million international arrivals in 2023, closely followed by Spain at approximately 85 million. European nations heavily dominate the top ten tier, capturing six out of the ten spots and proving that Western and Mediterranean Europe remain the primary epicenters for international travel infrastructure. For business analysts in the hospitality, aviation, and retail sectors, this highlights specific high-density geographic markets where resource allocation and expansion campaigns yield the most reliable commercial returns.

---

### Insight 2: Global Tourism Trend and Post-Pandemic Stabilization
![Global Tourism Trend](global_tourism_trend.png)

> The descriptive statistics show a massive surge in global international tourist arrivals between 2022 and 2023, jumping from roughly 530 million to over 650 million arrivals. Following this aggressive recovery period, the predictive data for 2024 shows a plateauing trend, with volume remaining relatively flat compared to the previous year. For business analytics and market forecasting, this indicates that the post-pandemic travel boom has officially normalized, shifting the market into a stable, highly predictable baseline for operational planning.
