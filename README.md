**You can find my project notebook and cleaned dataset here:**
https://hub.labs.coursera.org:443/connect/sharedyttdtidx?forceRefresh=false&path=%2Fnotebooks%2Fonline_retail.ipynb&isLabVersioning=file-prep


**Solution Summary**
I analyzed real transactional data from an online retail company using Python, Pandas, and Seaborn.
The goal was to uncover sales trends, understand customer behavior, and identify popular products to help improve the store’s performance.

**📊 Key Findings:**
November had the highest revenue, driven by holiday shopping.

Sales peak on Thursdays, with most purchases made between 6 AM and 12 PM, peaking at noon.

The UK accounts for the majority of sales.

Top-selling products include craft items and giftware.

Detected extreme outliers, such as a single order of 80,995 units, which could distort overall insights.

**📌 Recommendations:**
Prepare sufficient stock and launch marketing campaigns before November.

Time promotions to reach shoppers early in the morning.

Focus on top-selling products for bundles or featured deals.

Validate large transactions to prevent reporting errors.

Explore targeted promotions for international markets.

**🧩 My Approach**
**1️⃣ Data Loading & Cleaning**

Loaded the dataset into a Pandas DataFrame.

Converted date columns and handled missing values (notably CustomerID).

Created new columns (TotalPrice, Month, DayOfWeek, Hour) for deeper trend analysis.

**2️⃣ Exploratory Data Analysis (EDA)**

Checked for missing data and removed or flagged invalid rows.

Used descriptive statistics to understand quantity, unit price, and revenue distributions.

Created time-based aggregates to find trends by month, weekday, and hour.

**3️⃣ Data Visualization**

Plotted histograms, bar charts, and boxplots to reveal trends and outliers.

Highlighted how extreme values (e.g., bulk orders of 80,000+ units) distort totals.

Compared distributions with and without outliers for clear reporting.

**4️⃣ Insights & Business Recommendations**

Translated findings into practical suggestions to support inventory management, marketing timing, and sales strategies.

Emphasized data validation and outlier handling to ensure reliable business reporting.

**🎯 Why This Matters**
This project shows how raw sales data can guide data-driven decisions. I used real EDA techniques to spot trends, outliers, and opportunities that help optimize revenue and customer satisfaction.

**🚀 Next Steps**
If I continued this project, I’d:

Build dashboards for real-time monitoring.

Automate outlier detection and flagging.

Develop customer segmentation for targeted marketing
