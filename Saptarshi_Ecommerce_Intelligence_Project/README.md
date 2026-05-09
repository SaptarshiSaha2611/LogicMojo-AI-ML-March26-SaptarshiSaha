# 📊 E-Commerce Business Intelligence & EDA Pipeline

## 📖 Project Overview
This project is an end-to-end Data Engineering and Exploratory Data Analysis (EDA) pipeline built for a Brazilian E-Commerce platform. The goal of this project was to transform raw, fragmented transactional data into actionable strategic recommendations for business executives. 

By cleaning, engineering, and merging 9 disparate datasets (over 100,000 orders), this project uncovers critical insights regarding customer retention, geographic logistics, product performance, and seller risk.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Local Python Script / Jupyter

## 🗂️ The Dataset
The raw data consists of 9 separate CSV files representing over 100k anonymized e-commerce orders, including details on:
* **Customers & Sellers:** Geographic locations (States) and unique IDs.
* **Orders:** Purchase timestamps, exact delivery dates, and freight costs.
* **Products:** Category translations and item pricing.
* **Reviews:** Customer satisfaction scores (1 to 5 stars).

## 💡 Executive Insights & Strategic Recommendations
*(Note: These insights were generated directly from the analysis charts located in the `Visualizations` folder).*

### 1. The "One-and-Done" Retention Problem
* **Insight:** The vast majority of the user base consists of one-time shoppers. However, the top 28% of "High-Value" customers generate the bulk of gross revenue. 
* **Recommendation:** Implement an automated email retention campaign offering a 15% discount exactly 7 days after a first purchase to incentivize repeat business.

### 2. Logistics Dictates Brand Perception (The "Staircase of Doom")
* **Insight:** Our correlation heatmap and bar charts prove a severe negative correlation between delivery times and review scores. Orders exceeding 14 days of transit almost universally result in a 1-star review. Furthermore, fragile categories (e.g., Electronics, Furniture) show a disproportionate amount of dissatisfaction.
* **Recommendation:** Heavily incentivize top sellers to utilize fulfillment centers strictly within the primary customer hub (São Paulo) to slash freight costs and delivery times. Enforce stricter packaging quality control on high-risk, fragile items.

### 3. Seller Concentration Risk
* **Insight:** A small fraction of top sellers brings in a disproportionate amount of platform revenue. 
* **Recommendation:** Assign dedicated VIP account managers to the top 10 highest-earning sellers to ensure platform loyalty and mitigate the risk of them leaving for a competitor.

### 4. Optimized Advertising Windows
* **Insight:** Customer order volume exhibits a clear daily rhythm, peaking strictly between 10:00 AM and 4:00 PM.
* **Recommendation:** Shift social media advertising budgets to trigger specifically during this 6-hour window to maximize Return on Ad Spend (ROAS).

## 🚀 How to Run the Pipeline
1. Clone the repository:
   ```bash
   git clone [https://github.com/SaptarshiSaha2611/LogicMojo-AI-ML-March26-SaptarshiSaha.git](https://github.com/SaptarshiSaha2611/LogicMojo-AI-ML-March26-SaptarshiSaha.git)
