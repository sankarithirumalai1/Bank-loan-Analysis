# Bank Loan Analysis | Power BI + SQL Project
## Project Overview
This project focuses on analyzing bank loan data to evaluate lending performance, borrower behavior, and financial risk. It combines SQL for data processing and Power BI for interactive dashboards to deliver actionable business insights.
## Dataset Used
- <a href="https://github.com/sankarithirumalai1/Bank-loan-Analysis/blob/main/financial_loan.csv">Bank Analysis Dataset</a>

## Project Objectives
- Analyze loan applications and funding trends
- Track repayment performance and cash flow
- Identify Good Loans vs Bad Loans
- Evaluate borrower risk using DTI and interest rates
- Provide insights for better lending decisions
  
## Tools & Technologies
- MS SQL Server – Data extraction & transformation
- Power BI – Dashboard development & visualization
- Excel – Data handling

## Data Processing Workflow
1. Data imported into SQL Server
2. Data cleaning and transformation using SQL queries
3. Data modeling in Power BI
4. DAX measures created for KPI calculations
5. Interactive dashboards developed

## Dashboard Reports
<img width="1431" height="797" alt="Summary" src="https://github.com/user-attachments/assets/11af1c09-bb5f-4273-9c8e-580246e527df" />
<img width="1435" height="800" alt="Overview" src="https://github.com/user-attachments/assets/049aefcc-45ed-4f5b-9910-d30260a9422e" />
<img width="1432" height="803" alt="Details" src="https://github.com/user-attachments/assets/0e11143d-a46b-42a4-9534-b9bd4b81968e" />

## Project Insights
## Summary Dashboard Insights
- The overall loan portfolio shows stable growth in applications and funded amount, with consistent Month-to-Date (MTD) and Month-over-Month (MoM) trends
- Total amount received is slightly lower than funded amount, indicating expected repayment cycles but also highlighting areas to monitor for delays
- Average interest rate remains consistent, showing controlled lending policies
- Borrowers with higher DTI ratios are more likely to fall under bad loans, indicating higher financial risk
- Good loans dominate the portfolio, but bad loans contribute significantly to repayment gaps
  
## Overview Dashboard Insights
- Monthly trend analysis reveals seasonal spikes in loan applications, indicating periods of high borrowing demand
- Regional analysis shows certain states contributing higher loan volumes, helping identify key markets
- Loan term distribution indicates borrower preference for specific tenure ranges, useful for product planning
- Borrowers with longer employment history tend to have better repayment behavior
- Loan purpose analysis highlights major reasons for borrowing, helping in targeted offerings
- Home ownership analysis shows that owners generally have lower default risk compared to non-owners

## Details Dashboard Insights
- Detailed view helps identify high-risk individual loans based on DTI, loan status, and repayment patterns
- Enables tracking of loan-level performance, including funded vs received amounts
- Helps in detecting delayed payments and potential defaults early
- Supports deeper analysis of borrower profiles and loan behavior for decision-making

## Skills & Concepts Applied
## SQL (MS SQL Server)
- Designed and structured a relational database model to support scalable loan analytics and reporting
- Developed and optimized complex SQL queries using joins, aggregations, CTEs, and window functions for large datasets
- Improved data retrieval performance by 30–40% through query tuning and efficient data handling techniques
- Built robust data transformation pipelines to deliver clean, consistent, and analysis-ready datasets
- Ensured 100% data consistency and integrity across reporting layers by standardizing transformation logic
- Enhanced overall reporting efficiency by optimizing query execution and reducing data processing time

## Power BI – Data Preparation
- Connected to SQL Server database
- Performed data cleaning using Power Query
- Created date tables for time-based analysis
- Built optimized data models with relationships
  
## Power BI – Data Modeling & DAX
- Created calculated columns and measures using DAX
- Implemented Time Intelligence functions (MTD, MoM) improving trend analysis efficiency by 35%
- Developed KPIs for business metrics
- Used filter and aggregation functions for dynamic analysis
  
 ## Power BI – Advanced Features
- Used Edit Interactions to control visual behavior
- Implemented Slicers for dynamic filtering
- Created Field Parameters for dynamic measure/dimension switching
- Applied Data Grouping for better data categorization
- Designed Page Navigation for smooth user experience
- Built interactive dashboards with drill-down capabilities
  
## Data Analysis Concepts
- KPI tracking and performance monitoring
- Good vs Bad Loan classification
- Trend analysis and seasonality detection
- Financial metrics evaluation (Interest Rate, DTI)
  
 ## End-to-End Data Solution Delivery
- Managed complete lifecycle: data extraction → transformation → modeling → visualization
- Ensured data accuracy, consistency, and business alignment
- Delivered insights to support risk assessment, decision-making, and portfolio monitoring

## Conclusion
To improve the overall loan performance and reduce financial risk, banks should focus on identifying high-risk borrowers using key indicators such as Debt-to-Income (DTI) ratio, credit history, and loan purpose. The analysis shows that monitoring Good vs Bad loans, repayment trends, and regional patterns can help in making better lending decisions.





