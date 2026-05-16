# CUSTOMER-RFM-ANALYSIS

# Table of Contents
- [Analysis Overview](#analysis-overview)  
- [Business Objectives](#business-objectives)  
- [Data Source](#data-source)  
- [Preparation Tool](#preparation-tool)  
- [Data Processing](#data-processing)  
- [Data Modeling](#data-modeling)  
- [Skills Demonstrated](#skills-demonstrated)  
- [Insights from the Dashboard](#insights-from-the-dashboard)  
- [Recommendation](#recommendation)    
- [Dashboard](#dashboard)  


# Analysis Overview
This project analyzes customer purchasing behavior using the RFM (Recency, Frequency, Monetary) model to identify high-value customers, inactive customers, and customer segments that require different business strategies.

# Business Objectives
* Identify high-value customers based on purchasing behavior and spending patterns.
* Detect inactive and at-risk customers who may require retention strategies.
* Analyze customer distribution across different RFM segments.
* Understand which customer groups contribute the most revenue and profit.
* Support data-driven marketing and customer engagement decisions.
* Improve customer retention through targeted business strategies.
* Provide actionable business insights using customer segmemtation Analysis

# Data Source 
The dataset used for this project was obtained from Kaggle and imported into Microsoft Power BI as a Text/CSV file. The dataset contains ecommerce transactional data used to analyze customer purchasing behavior and perform RFM (Recency, Frequency, Monetary) segmentation.

# Preparation Tool 
The dataset was cleaned and prepared in Microsoft Power BI using Power Query to ensure accuracy, consistency, and readiness for analysis.
# Data Processsing
The following data cleaning processes were performed:
* Checked for duplicate records.
* Standardized column names and formatting for consistency.
* Cleaned and corrected inconsistent date columns.
* Removed unwanted and irrelevant columns.
* Verified appropriate data types for numerical and date fields.

After the cleaning process, the transformed dataset was loaded into Power BI for modeling and analysis.
![]()


# Data Modeling
I modeled the data by creating a one-to-many relationship between the ecommerce fact table and two supporting  tables, allowing the fact table to serve as the “many” side while the other tables act as the “one” side for efficient filtering and analysis.
Several DAX measures and calculated tables were created to support the RFM analysis and dashboard development.

DAX Measures Created
Total Revenue,
Total Profit,
Champions Percentage,
Lost Customers Percentage


## Date Table
A dedicated Date Table was created to support time intelligence analysis and improve data modeling efficiency.

Customer RFM Table

A Customer RFM Table was created containing:
Customer RFM Table
* Recency
* Frequency
* Monetary Value
* Recency Score
* Frequency Score
* Monetary Score
* Customer Segmentation

The RFM model was used to categorize customers into different behavioral segments such as Champions, Loyal Customers, Regular Customers, At Risk Customers, and Lost Customers based on their purchasing activity, purchase frequency, and spending patterns.

# Skills Demonstrated
* Data Cleaning & Preparation in Power Query
* Dax Calculation
* Business Intelligence: KPI design, executive dashboard development.
* Analytical Storytelling
* Critical Thinking
* Problem Solving
# Insights From the Dashboard

## KPI Overview
### Total Customers: 
The dashboard shows that the business has aproximately 42,050 customers. This indicates that the company has built a significant customer base large enough for meaningful customer segmentation and behavioral analysis.
#### Business Impact:
Having a large customer base is beneficial, but it also raises an important business question:
Are all customers equally valuable to the business?
The dashboard answers this question through customer segmentation.
### Total Revenue:
The company generated approximately $23.16 million in revenue.
This reflects strong customer purchasing activity and business scale.
However, revenue alone does not provide a complete understanding of business performance.

#### Business Impact:
High revenue does not always translate into high profitability.
This is why profit analysis is also included in the dashboard.

### Total Profit: 
The business retained approximately $2.61 million as profit.
The difference between revenue and profit suggests that operational costs, discounts, and other expenses impact overall profitability.

#### Business Impact:

This KPI emphasizes the importance of focusing not only on sales generation but also on profitability optimization.
### Champions %: 
Approximately 17% of customers fall into the Champions segment.
These customers are:
   * Highly active
   * Frequent buyers
   * High spenders
A relatively small customer group contributes significantly to business value.
####  Business Impact
Champions are among the most valuable assets of the business.
Losing these customers could have a major impact on: 
* Revenue
* Profitability
* Customer loyalty.

### Lost Customers %:
Approximately 25% of customers are Lost Customers.

These customers show:
  * Low engagement
  * Inactive purchasing behavior
  * Weak customer activity
A quarter of the customer base appears disengaged.

  #### Business Impact
This may indicate: weak retention strategies, poor customer experience, ineffective re-engagement efforts.

# Revenue by Segment
This chart shows how much revenue each customer segment contributes to the business.
The Champions segment contributes the highest revenue among all customer groups.
Regular and Loyal customers also contribute meaningfully, while Lost Customers contribute the least.

## Business Interpretation
This confirms that customer value differs significantly across segments.
The business is highly dependent on a smaller group of high-performing customers.

## Business Impact
Understanding revenue contribution helps the company:
* Prioritize high-value customers
* Improve retention strategies
* Allocate marketing resources effectively
* Identify customer growth opportunities

# Profit by Segment
This chart analyzes profit contribution across customer segments.

## Key Findings
Champions customers generate the highest profit contribution.
At Risk and Lost customers contribute significantly less to profitability.

### Business Interpretation
Revenue alone does not define customer quality.
Some customer groups may generate sales but contribute lower profitability.

### Business Impact
This insight helps the business:
* Identify truly profitable customers
* Reduce low-value customer acquisition costs
* Improve operational efficiency
* Focus on profitable customer relationships

# Segment Distribution
The segment distribution chart shows how customers are distributed across different RFM segments.

## Key Findings
The dashboard reveals:
* A large number of Regular customers
* A significant Lost customer segment
* A smaller Champions customer group
Business Interpretation

### Business Impact
The greatest opportunity for growth may come from:
* Converting Regular customers into Loyal customers
* Retaining Champions customers
* Reducing customer churn

# Customer RFM Table
The Customer RFM table provides detailed customer-level analysis.
It displays:

Customer ID
Segment
Recency
Frequency
Monetary value
Total profit contribution.
This table increases dashboard transparency by allowing users to inspect individual customer behavior.

## Business Impact
Businesses can use this information to:
* Identify high-value customers
* Monitor customer activity
* Track customer profitability
* Support targeted customer strategies.
  
