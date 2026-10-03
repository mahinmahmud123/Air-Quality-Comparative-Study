#  Comparative Air Quality Analysis: Beijing vs. Dhaka

A data-driven comparative study analyzing air pollution levels in Beijing (China) and Dhaka (Bangladesh) using WHO health risk standards.

## 📌 Project Overview
This project processes real-world air quality data from two major Asian cities to evaluate pollution severity. Instead of just plotting raw PM2.5 numbers, this study engineers a custom "Risk_Level" feature based on World Health Organization (WHO) guidelines to categorize daily air quality into meaningful health risks.

##  Key Findings
- Average PM2.5 Levels: Beijing (86.19 µg/m³) vs. Dhaka (105.50 µg/m³).
- Hazardous Days: Dhaka experiences a higher percentage of "Hazardous" air quality days (20.91%) compared to Beijing (16.94%).
- Data Insight: Both cities show a significant number of "Unhealthy" days, highlighting a critical need for environmental monitoring and policy intervention.

## 🛠️ Methodology & Feature Engineering
1. Data Ingestion: Loaded and merged multi-site environmental datasets.
2. Feature Engineering: Created a custom `Risk_Level` column by applying WHO threshold logic to raw PM2.5 values (Good, Moderate, Unhealthy, Hazardous).
3. Comparative Visualization: Generated statistical summaries and count plots to visualize the distribution of health risks across both regions.

##  Tech Stack
- Language: Python
- Libraries: Pandas (Data Manipulation), NumPy, Matplotlib & Seaborn (Visualization)

## 📊 Visualization
![Air Quality Comparison Graph](https://user-images.githubusercontent.com/your-username/your-image-link.png) 
(Note: The bar chart comparing WHO Health Risk Levels is generated in the Jupyter Notebook)
