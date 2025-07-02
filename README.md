# Marketing-Retail-Analytics- Customer Segmentation & Revenue Boosting
Performed Market Basket Analysis and RFM segmentation on auto parts and grocery POS data. Delivered marketing strategies and cross-selling combos to enhance customer retention and store revenue.


---

## 🚀 Project Summary
📈 **Repo:** `Marketing-Retail-Analytics-Customer-Segmentation-Revenue-Boosting`  
This project explores **customer behavior and sales optimization** across two retail sectors:

1. **Auto Parts Manufacturer (Part A)** — Used **RFM analysis** to segment customers and recommend targeted marketing strategies.
2. **Grocery Store (Part B)** — Performed **Market Basket Analysis** to design combo offers and cross-selling opportunities.

✅ These insights help businesses enhance **customer retention, engagement, and sales growth**.

---

## 🏪 Part A: RFM Analysis for Auto Parts Transactions

### 🔍 Overview
- **Data:** 3 years of POS transactions (2,747 rows, 20 features).
- **Goal:** Identify key customer segments (best, loyal, churning, lost) using **RFM scores** and drive marketing actions.

### 📊 Highlights
- **KNIME workflows** for data preprocessing, auto-binning & RFM scoring.
- Identified:
  - 🔝 **Top customers** (Order #10348, #10358) — frequent, high-value buyers.
  - 💔 **Churning & lost customers** needing re-engagement offers.
  - ❤️ **Loyal customers** showing repeat high spending.

### 🚀 Business Recommendations
- Offer **exclusive deals** to loyal customers.
- Use **personalized discounts** to win back churned segments.
- Plan **seasonal campaigns** to address November sales dips.

### 📈 Key Visualizations
![WEEKLY & MONTHLY TRENDS IN SALES](https://github.com/user-attachments/assets/7f81fc95-310f-4eff-8b18-fd1a1993e51a)

![QUARTERLY AND YEARLY SALES TREND](https://github.com/user-attachments/assets/d1afc42d-2258-46cd-af32-3f2924310fc2)

![BIVARIATE ANALYSIS: 
SALES ACROSS DIFFERENT 
CATEGORIES](https://github.com/user-attachments/assets/530d2d69-a90b-4df2-9e34-e41bbc97eaa9)

![BI VARIATE ANALYSIS:
 SALES ACROSS COUNTRIES](https://github.com/user-attachments/assets/f8f133bf-bafb-424c-a461-ab4a9a6bd131)

![KNIME WORKFLOW](https://github.com/user-attachments/assets/66371bdf-827f-4e9a-91d3-16663796d7b6)

---

## 🛒 Part B: Market Basket Analysis for Grocery Store

### 🔍 Overview
- **Data:** 6 years POS data with ~20,641 transactions.
- **Goal:** Discover frequent product combinations & propose **combo offers** to maximize basket value.

### 📊 Highlights
- Used **KNIME** for:
  - Aggregating orders, generating association rules.
  - Set **min support = 0.1**, **confidence = 0.4** to filter meaningful rules.
- Top rules (with lift >1.2) included:
  - `Mixes -> Dishwashing Liquid`
  - `Shampoo -> Juice`
  - `Yogurt -> Juice`

### 💡 Suggested Combos
| Combo Items                  | Offer                        |
|-------------------------------|-----------------------------|
| Mixes + Dishwashing Liquid    | Buy Mixes, Get 20% off Liquid |
| Yogurt + Juice                | Buy Yogurt, Get 20% off Juice |
| Pasta + Paper Towels          | Buy Pasta, Get 15% off Towels |

✅ **Impact:** Designed to **boost cross-selling** and increase average transaction value.

### 📈 Key Visualizations
Plese Refer the pdfs attached to the repository

---

## 🛠️ Tools & Skills Covered
- 🐍 Python: pandas, numpy, matplotlib, seaborn
- 🟡 **KNIME:** RFM segmentation, auto-binner, association rules mining
- 📊 Customer Segmentation & Lifetime Value
- 🔍 Market Basket & Cross-Sell Strategy

---

## ⚙️ How to Run
📌 This repo contains KNIME workflows (`.knwf`) and Python notebooks.
- Open `.knwf` files in KNIME to reproduce segmentation or association rule results.
- Use `MRA Project 2.ipynb` for supplementary Python EDA.

---

## 🤝 About Me
I completed this project end-to-end on my own, showcasing strong data analytics, marketing strategy, and data storytelling skills.

🔗 [LinkedIn](https://linkedin.com/in/yourprofile)

---

✅ **Thanks for exploring my retail analytics projects!**
