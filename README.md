# 📊 A/B Testing on Marketing Campaigns (Facebook vs AdWords)

## 🧠 Project Overview
This project analyzes and compares the performance of two marketing campaigns — **Facebook Ads** and **Google AdWords** — over a one-year period (2019).  
The primary objective is to determine **which platform delivers better ROI** in terms of clicks, conversions, and cost-effectiveness.

By conducting exploratory analysis, visualization, and hypothesis testing, we identify the **most effective advertising channel** and provide actionable business insights for marketing strategy optimization.

---

## 🎯 Business Problem
A marketing agency wants to optimize its ad budget allocation between **Facebook** and **AdWords** campaigns.  
The question:  
> Which ad platform is more effective in driving conversions and maintaining cost efficiency?

---

## 🧾 Dataset Description
**File:** `marketing_campaign.csv`  
**Rows:** 365 (daily data for 2019)

| Feature | Description |
|----------|-------------|
| Date | Daily record (Jan 1, 2019 – Dec 31, 2019) |
| Ad Views | Number of times the ad was viewed |
| Ad Clicks | Number of clicks received |
| Ad Conversions | Number of conversions achieved |
| Cost per Ad | Daily cost of running the ad |
| CTR (Click Through Rate) | Clicks / Views |
| Conversion Rate | Conversions / Clicks |
| CPC (Cost per Click) | Average cost per click |

---

## 🧩 Tools & Libraries Used
- **Python**
- **Pandas**, **NumPy** – Data cleaning & manipulation  
- **Matplotlib**, **Seaborn** – Data visualization  
- **SciPy**, **Statsmodels** – Hypothesis testing & statistical analysis  
- **Scikit-learn** – Regression modeling  
- **Jupyter Notebook**

---

## 📈 Methodology

### 1. Data Cleaning & Preparation
- Parsed dates, handled missing values, ensured numeric consistency.

### 2. Exploratory Data Analysis (EDA)
- Compared click-through rates (CTR), conversion rates, and CPC between platforms.  
- Visualized time trends and cost distributions.

### 3. A/B Hypothesis Testing
- Tested whether differences in conversion rates and CPC are statistically significant.  
- Used two-sample t-tests and p-value interpretation.

### 4. Insights & Recommendations
- Interpreted trends, seasonality, and ROI implications.

---

## 📊 Key Findings
- **Facebook Ads** demonstrated a higher **conversion rate** but slightly higher **cost per conversion (CPC)**.  
- **AdWords** performed better in **CTR**, but with lower overall conversions.  
- Conversion activity was **highest on Mondays and Tuesdays**.  
- **May and November** were the most **cost-efficient months** (lowest CPC).  
- A significant **long-term relationship** exists between ad spend and conversions (based on cointegration test).

---

## 💡 Business Insights
- Allocate more ad budget to **Facebook during May & November** to maximize ROI.  
- **Reallocate weekday ad spend** to Monday–Tuesday for improved conversion rates.  
- Maintain a **balanced cross-platform strategy** to stabilize long-term performance.

---

## 🧮 Statistical Summary

| Metric | Statistical Test | Key Result |
|--------|------------------|-------------|
| Conversion Rate Difference | Two-sample t-test | p < 0.05 → Significant |
| Cost–Conversion Relationship | Cointegration Test | Stable long-term relationship |
| CPC Trend | Time Series Decomposition | Seasonal variations identified |

---

## 🧰 How to Run the Project

1. **Clone this repository**
   ```bash
   git clone https://github.com/bytebyrajeev/AB-Testing-Marketing-Campaigns.git
   ```

2. **Navigate into the folder**
   ```bash
   cd AB-Testing-Marketing-Campaigns
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Open Jupyter Notebook**
   ```bash
   jupyter notebook "AB Testing (Marketing Campaigns).ipynb"
   ```



---

## 🚀 Skills Demonstrated
- A/B Testing & Statistical Inference  
- Exploratory Data Analysis (EDA)  
- Business Intelligence & Data Storytelling  
- Data Visualization & Insight Communication  
- Python Data Stack (Pandas, Seaborn, Statsmodels)

---

## 🧾 Author
**Your Name**  
📧 rajeev108.tech@gmail.com  
🔗 www.linkedin.com/in/rajeev-tech1
📂 https://github.com/bytebyrajeev/

