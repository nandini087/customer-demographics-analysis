# Power-BI-report-1 
📊 Customer Demographics & Income Analysis – Power BI Dashboard

This is a basic Power BI dashboard project that explores customer demographic data such as income, marital status, education, and location. It serves as a beginner-friendly visual analytics report.

🎯 Objective

To explore and visualize how customer income and demographic characteristics (like marital status, education, and geography) are distributed in the dataset and how they relate to each other.

📁 Dataset Information

**File Name:** `marketing_customer_data_uncleaned.csv`  
**Columns Included:**
- `ID`
- `Year_Birth`
- `Education`
- `Marital_Status`
- `Income`
- `Kidhome`
- `Teenhome`
- `Dt_Customer`
- `Country`
- `Complain`
- `Successful_Campaigns`

---

## 📌 Key Insights

- 🟨 Spain (SP) has the highest number of customers and income contribution.
- 💍 Married and Together customers tend to have the highest income.
- 🎓 Most customers have Graduation-level education, followed by PhD.
- 🧒 Married people are more likely to have teenagers at home.
- 🌍 Country-wise income and customer distribution varies significantly.
- ❌ Some entries had missing or null income values which were cleaned during transformation.

---

## 📊 Visuals in the Dashboard

| Visual Title                             | Description                                             |
|------------------------------------------|---------------------------------------------------------|
| Total Income by Marital Status           | Shows income distribution across different relationships |
| Customer Distribution by Country         | Donut chart representing number of customers per country |
| Education Levels of Customers            | Education-wise customer count                           |
| Country-wise Customer Breakdown          | Pie chart summarizing country-wise count                |
| Total Income Contribution by Country     | Highlights which countries bring the most revenue       |
| Households with Teenagers by Marital Status | Teenhome presence across marital status               |

---

## ⚙️ Tools & Techniques Used

- Microsoft Power BI Desktop
- Data Cleaning using Power Query
- Data Type Conversion (e.g., Income to Currency)
- Bar Charts, Donut Charts, Pie Charts, and Table Views
- Null/NA row removal

---

📂 Files Included

-  Dashboard screenshots
- `marketing_customer_data_uncleaned.csv` – Original dataset (cleaned before use)
- `README.md` – Project documentation

---

📌 Future Ideas

- Add analysis for Complaint trends and Campaign Success
- Create slicers for dynamic filtering (e.g., by country or education)
- Export summary reports for stakeholders

