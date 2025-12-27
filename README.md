📊 Marketing Campaign Results Dashboard — Power BI

This project presents an interactive Power BI dashboard that analyzes marketing campaign performance, customer demographics, and spending patterns.
It transforms raw customer, product, and campaign data into clear insights that help businesses make data-driven decisions.

🔍 Project Objective

To analyze marketing campaign data and answer questions like:

Which campaigns performed best?

How much are customers spending, and on what products?

Which channels generate the most purchases?

How does spending vary by age, income, and education?

What is the overall campaign success rate?

📂 Dataset Overview

The dataset links to the 4Ps of Marketing:

Category	Fields
People	Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome
Product	MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds
Place	Web, Catalog, Store, Deals purchases
Promotion	Campaign results, Recency, Acceptance, Responses
🧹 Data Cleaning & Transformation (Power Query)

Key steps:

1️⃣ Remove null rows & duplicates
2️⃣ Convert data types (dates, numeric fields)
3️⃣ Create calculated columns and measures
4️⃣ Standardize categories (Education, Marital Status, etc.)
5️⃣ Build modeling relationships between tables

The relationships were modeled so that all customers appear even if they didn’t purchase.

📐 Key Measures & KPIs (Power BI)

Some of the important KPIs:

Total Amount Spent

Total Customers

Total Products

Average Spend per Customer

Total Campaigns

Campaign Success / Acceptance Rate

Spending by Product

Spending by Age & Income Levels

Channel Performance

The Campaign Success Rate was calculated as
Accepted Campaigns / Total Campaign Offers * 100

📊 Dashboard Visuals

The dashboard contains:

💲 Total Spend by Product

👥 Spending by Age Group

🎓 Spending by Age & Education (Scatterplot)

🛒 Channel Performance (Store, Web, Catalog, Deals)

💰 Spending by Income Level

📈 Campaign Success Rate

🌍 Country Filter for regional insights

Each visual helps stakeholders quickly understand where value is created.

🛠️ Tools Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Excel / CSV Dataset

🚀 How to Use

Download the .pbix file from this repository

Open it in Power BI Desktop

Interact with slicers and visuals to explore insights

Modify measures or visuals if needed

💡 Insights Gained

✔️ Customers aged 36–50 spend the most
✔️ Store channel generates the highest purchases
✔️ Highest spending happens among incomes 50,000–75,000
✔️ Wine is the top-selling product
✔️ Campaign success varies across groups — targeted strategies work better

🔮 Possible Enhancements

Add predictive modeling for campaign performance

Integrate live data sources

Build comparative dashboards (before vs after campaign)

Add customer segmentation clustering
