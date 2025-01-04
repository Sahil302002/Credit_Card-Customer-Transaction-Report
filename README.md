## **Project 2: Financial Domain Power BI Project**:

This project focuses on analyzing **Credit Card Transactions** and **Customer Details** data to derive valuable insights related to customer behavior, financial transactions, and credit usage patterns. The project leverages **Power BI** and **SQL Server** to process and visualize large datasets, enabling businesses to make data-driven decisions related to customer acquisition, retention, and credit management.

The dataset comprises two key tables: **Credit Card** data, which includes detailed records on credit card transactions, fees, and usage patterns, and **Customer Details**, which contains demographic, financial, and satisfaction data for each cardholder. This analysis aims to provide insights on customer segmentation, credit card usage trends, and the impact of various factors such as income, age, and card category on customer behavior and satisfaction.

By utilizing Power BI’s advanced visualizations and DAX queries, the project helps in identifying actionable insights, such as the most profitable customer segments, transaction behaviors, credit utilization trends, and customer satisfaction drivers. This allows for better-targeted marketing efforts, improved customer service strategies, and optimized credit offerings.

---

## **Project Overview**:

In this finance-related data analysis project, the main goal was to analyze and visualize **Credit Card Transactions** and **Customer Data** to derive insights on customer behavior, card usage, and financial trends. The project utilized **Power BI** for visualization, connected to **SQL Server** to manage and process large datasets.

The project involved several important steps:

1. **Data Import and Connection**: Data was imported into **SQL Server** from CSV files containing detailed records of credit card transactions and customer information. Power BI was then connected to SQL Server to retrieve and process the data.
2. **Data Transformation and Processing**: Using **Power Query**, data was cleaned, transformed, and enhanced by adding new calculated columns. This included creating age and income groups for customer segmentation.
3. **DAX Queries**: Various DAX queries were used to analyze transaction patterns, calculate utilization ratios, and create meaningful aggregations that can provide deeper insights into customer behavior.
4. **Visualizations**: After processing the data, Power BI was used to create dynamic dashboards, presenting key metrics such as transaction volumes, total spending, customer satisfaction scores, and delinquency rates.

The final output of this project was an interactive dashboard that allows stakeholders to analyze various aspects of credit card usage and customer demographics.

- Dataset Used in this Project
<a href = "credit_card.csv">Credit_Card_Dataset</a>
<a href = "customer.csv">Customer_Dataset</a>

## **Tasks Completed in This Project**:

1. **Data Import and Integration**:
    - Imported **Credit Card** and **Customer Details** data into **SQL Server**.
    - Established a connection between **Power BI** and **SQL Server** for data retrieval.
2. **Data Transformation**:
    - Cleaned and processed the data using **Power Query**.
    - Created **Age Group** and **Income Group** columns in the **Customer Details** table using **Custom Columns**.
3. **DAX Querying**:
    - Used **DAX** to calculate key metrics, such as **credit utilization ratio**, **total transaction amount**, and **interest earned**.
    - Created calculated fields to enable better analysis of customer spending patterns and credit behavior.
4. **Data Analysis**:
    - Segmented customers by age and income to analyze spending behaviors.
    - Analyzed transaction volume and total transaction amounts to identify trends.
    - Investigated delinquency rates and their impact on customer retention and acquisition.
5. **Visualization Creation**:
    - Developed dynamic dashboards and reports in **Power BI** to visualize trends, customer demographics, transaction volumes, and customer satisfaction scores.
    - Created visualizations such as **bar charts**, **line graphs**, and **pie charts** to represent key data points.
6. **Insights Extraction**:
    - Identified profitable customer segments based on card category, income group, and transaction behavior.
    - Derived insights related to credit utilization patterns and the impact on customer satisfaction.
    - Provided recommendations for targeted marketing and customer retention strategies based on demographic analysis.

The project successfully combined data analysis, visualization, and actionable insights to help stakeholders better understand customer behavior, financial trends, and optimize credit card services.

<a href = "Credit Card Report.pbix">Credit_Card_Dashboard_Power_BI_File</a>

# DASHBOARD SUMMARY

## Credit Card Transaction Report

This dashboard provides a comprehensive analysis of credit card transactions. Below are the insights and explanations based on the visual elements in the report:

### **Key Metrics**

1. **Total Revenue:** $55.32M
2. **Total Interest Earned:** $7.84M
3. **Total Transaction Amount:** $44.52M
4. **Transaction Count:** 655.7K

These key performance indicators (KPIs) summarize the overall performance of the credit card portfolio.

### **Dynamic Slicers for Enhanced Revenue Insights**

To enhance the analytical capabilities of the dashboard, I have incorporated Four **tree maps** for **Quarters**, **Card Type**, **Gender**, and **Income Group**, functioning as interactive tilt slicers. These elements provide a dynamic way to filter and explore data. 

Additionally, a **dropdown slicer** is included, enabling stakeholders and the CEO to analyze individual categories or combined segments in depth.

 By utilizing these tools, users can gain a clear and actionable understanding of revenue breakdowns across various categories and demographics, facilitating more informed decision-

### **Card Category Insights**

- **Blue Cards:** Generate the highest revenue at $46M, followed by Silver at $6M, Gold at $2M, and Platinum at $1M.
- **Transaction Patterns:**
    - Blue cards dominate total transaction amount ($3.69M).
    - Silver cards generate significant interest ($8.12M), likely due to higher outstanding balances.

### **Quarterly Trends (QTR Wise Revenue and Transaction Count)**

- **Revenue:**
    - Peak revenue of $14.2M in Q3, followed by $14.0M in Q1.
    - Q4 saw a slight decline to $13.3M, indicating seasonal fluctuations.
- **Transaction Count:**
    - Transactions peaked at 164.2K in Q3.
    - Q4 saw a decline in both transaction count and revenue, suggesting lower activity during this period.

### **Revenue by Chip Type**

- **Swipe Transactions:** Account for the highest revenue ($34.913K), emphasizing customer preference for physical card swipes.
- **Chip Transactions:** Contribute $16.967K, indicating a moderate adoption of secure chip technology.
- **Online Transactions:** Minimal revenue of $3.436K, suggesting an opportunity to improve online transaction adoption.

### **Revenue by Expenditure Type**

- **Bills:** Lead in revenue generation ($14M).
- **Entertainment and Fuel:** Both generate $10M and $9M respectively.
- **Travel:** Accounts for only $6M, likely impacted by limited travel-related spending or seasonal factors.

### **Revenue by Education Level**

- **Graduates:** Contribute the highest revenue ($22M).
- **High School and Post-Graduates:** Generate $11M and $3M respectively, showing a skew towards higher education levels.
- **Uneducated:** Contribute $8M, indicating a broad customer base.

### **Revenue by Job Type**

- **Business Professionals:** Generate $17.388K, the highest among all job types.
- **White-collar and Self-employed:** Contribute $10.115K and $8.262K respectively.
- **Blue-collar Workers and Retirees:** Contribute the least ($6.904K and $4.535K).

### **Key Observations**

1. **Blue Card Dominance:** Blue cards are the most widely used and profitable, suggesting a large customer base for this category.
2. **Seasonal Trends:** Q3 is the best-performing quarter, potentially linked to festive seasons or increased spending.
3. **Underperformance in Online Transactions:** There's a clear gap in online transaction revenue, highlighting an area for digital growth.
4. **Highly Educated Customers:** Graduates contribute significantly to revenue, making them a critical target segment.

### **Recommendations**

1. **Promote Online Transactions:** Offer incentives for online usage to capture more digital spending.
2. **Focus on Education Levels:** Tailor marketing strategies towards graduates and high school customers.
3. **Seasonal Campaigns:** Leverage Q3 trends for festive promotions to maximize revenue.
4. **Blue Card Engagement:** Enhance rewards and loyalty programs for Blue cardholders to retain their dominance.

## Credit Card Customer Report

This dashboard provides an overview of credit card customer performance metrics, including revenue, income, interest earned, customer satisfaction, and detailed demographic insights across multiple categories. Key features include:

### KPI Metrics:

Total Revenue: $55.32M

Total Interest: $7.84M

Income: 575.9M

Average Customer Satisfaction: 3.19 (likely on a scale of 5)

### Interactive Insights: Analyzing Revenue Drivers Through Dynamic Slicers and Gender Breakdowns

- Additionally, I have incorporated three tree maps for **Quarters**, **Card Type**, **Gender**, and **Income Group**, which function as interactive slicers. These visual elements allow users to explore data dynamically, offering deeper insights into various segments. A dropdown slicer is also included, enabling stakeholders and the CEO to analyze individual categories or combined segments effectively.
- Furthermore, all visuals are equipped with **gender-specific legends**, ensuring that each breakdown view highlights which gender contributes the most to revenue, thereby enhancing targeted decision-making.

## Revenue Breakdown of Male and Female**:**

### **By Week**:

A fluctuating trend is visible, indicating seasonal variations or events influencing revenue.

### **By Age Group**:

 The highest revenue comes from the 41–50 and 51–60 age groups.

### **By Income Group**:

High-income customers contribute the most revenue ($22M).

### **By Dependents**:

 Customers with 2-3 dependents generate the highest revenue.

### **By Marital Status**:

 Married customers contribute slightly more revenue than single customers.

### **By Education Leve**l:

 Graduates and postgraduates generate the highest revenue.

### **Top 5 States by Revenue**:

Texas (TX), New York (NY), California (CA), Florida (FL), and New Jersey (NJ) lead in revenue generation.

### Customer Segmentation:

**Job Category**: Business professionals and white-collar workers generate the highest total revenue.

**Card Type:** Revenue is segmented by card types (Silver, Blue, Gold, and Platinum).

## Analysis & Insights

- **High Revenue from Specific Age Groups:**

The 41–60 age groups generate most of the revenue. These individuals are likely in their peak earning years, suggesting they are a key target segment.

- **Dependents Influence Revenue:**

Customers with 2–3 dependents generate the highest revenue, possibly indicating that families tend to spend more or use credit more frequently.

- **Education Level Matters:**

Graduates and postgraduates contribute the most revenue. This indicates a positive correlation between education level and credit card usage.

- **State-wise Performance:**

Texas, New York, and California are high-revenue states. Marketing efforts in these states are likely yielding good returns.

- **Job Categories:**

Business professionals and white-collar workers dominate revenue generation, making them key customer profiles.

---

## Recommendations

- **Target High-Earning Segments:**

Focus marketing campaigns on high-income groups and the 41–60 age bracket, as they provide the highest revenue.

- **Customer Retention Programs:**

Offer loyalty programs or exclusive perks for high-revenue groups (e.g., business professionals, white-collar workers, and graduates) to retain them.

- **Geographic Expansion:**

Since TX, NY, and CA are leading in revenue, consider expanding promotional activities and partnerships in nearby states with similar demographics.

- **Product Customization:**

Introduce customized credit card products or benefits tailored for families, as customers with dependents show significant spending behavior.

- **Monitor Revenue Trends:**

Since revenue fluctuates by week, analyzing the patterns further can help identify specific events or periods that drive higher credit card usage.

![Credit Card Transaction Report](https://github.com/user-attachments/assets/e3c56968-2a72-4c25-9e66-57917db551a6)


![Credit Card Customer Report](https://github.com/user-attachments/assets/64262f19-b627-4ede-a1ed-834ca0b07b6d)
