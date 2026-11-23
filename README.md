# Customer_Shopping_Behavior-SQL-POWERBI-PYTHON

## 📌 Overview
This project analyzes transactional records from **3,900 retail purchases** to uncover insights into customer demographics, seasonal revenue trends, product category satisfaction, payment preferences, and repeat buyer subscription behavior. The workflow covers end-to-end data cleaning in Python, relational querying in PostgreSQL, interactive dashboarding in Power BI, and executive storytelling via a structured project report and Gamma presentation.

---

## 📊 Dataset
- **Records & Features:** 3,900 rows and 18 columns.
- **Customer Attributes:** `customer id`, `age`, `gender`, `location`, `subscription status`.
- **Purchase Details:** `item purchased`, `category`, `size`, `color`, `season`, `purchase amount (usd)`.
- **Behavioral & Checkout Metrics:** `review rating`, `discount applied`, `promo code used`, `payment method`, `shipping type`, `previous purchases`, `frequency of purchases`.
- **Data Quality Note:** 37 missing values in `review rating` were handled during preprocessing.

---

## 🛠️ Tools & Technologies
- **Python (Pandas, Jupyter Notebook):** Exploratory Data Analysis (EDA), missing value imputation, and database ingestion.
- **PostgreSQL (pgAdmin 4):** SQL querying for seasonal, demographic, geographic, and behavioral analysis.
- **Power BI:** Interactive KPI cards, slicers, and category/demographic visual breakdowns.
- **Gamma & Google Docs:** Executive presentation deck and comprehensive analytical project report.

---

## 🔄 Project Steps
1. **Exploratory Data Analysis & Cleaning (Python):**
   - Loaded the raw dataset in Python using `pandas` and audited structure and summary statistics (`info()`, `describe()`).
   - Imputed 37 missing values in `review rating` using product-category median ratings.
   - Standardized column naming conventions for documentation and loaded the cleaned table (`customer`) into PostgreSQL via SQLAlchemy.
     
2. **SQL Business Analysis (PostgreSQL):**
   - Queried the `customer` table in pgAdmin 4 to evaluate revenue by gender and season, category review ratings, top 5 order locations, payment method usage, apparel size revenue, promo code usage among shoppers aged 30+, shopping frequency spending patterns, and repeat buyer subscription rates.
3. **Interactive Dashboarding (Power BI):**
   - Built an interactive dashboard featuring headline KPI cards (`3.9K` customers, `$59.76` average purchase amount, `3.75` average review rating) alongside dynamic slicers for Subscription Status, Gender, Category, and Shipping Type.
4. **Reporting & Presentation:**
   - Created the analysis report and a PowerPoint presentation summarizing key insights and business recommendations.
---

## 📈 Dashboard

<img width="1178" height="677" alt="image" src="https://github.com/user-attachments/assets/4538593c-2258-40b4-b76e-4a7064dff5a2" />

---

## 💡 Key Results & Recommendations
- **Repeat Buyer Subscription Opportunity:** Out of repeat buyers (>5 previous purchases), **2,518 remain unsubscribed** compared to **958 subscribed**, highlighting a major opportunity to offer targeted subscription perks at checkout.
- **Seasonal & Inventory Planning:** Prioritize inventory and marketing campaigns for top-performing clothing sizes (such as Size M) and peak revenue seasons.
- **Checkout & Promo Optimization:** Highlight top payment methods (such as PayPal and cards) to reduce checkout friction and focus promo code campaigns on high-response segments.

---

