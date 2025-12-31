# Customer Retention & Revenue Optimization Dashboard (Power BI)

## Problem Statement
Analyze customer behavior to identify churn patterns and revenue drivers
to support data-driven business decisions.

## Tools & Technologies
- Python (EDA & Data Cleaning)
- Snowflake( Data Storage )
- SQL
- Power BI (DAX, Data Modeling, Visualizations)


## Dataset
- Dimension Tables(dim_contract, dim_customers, dim_services)
- Fact Tables ( fact_subscription )


## Data Modeling
- Model design: Star Schema
- Relationship: One-to-many
- Filter: Single-direction 

## Key Insights
- Month-to-Month contracts contribute the highest customer base, indicating higher churn exposure compared to long-term contracts.
- Month-to-month contracts show the highest churn risk
- Customers using electronic check payments churn significantly more
- Fiber optic users account for the largest share of churned customers
- High revenue loss is driven by Month-to-Month contracts
- Two-Year contracts generate the highest revenue with lowest loss
- Electronic check users generate high revenue but pose higher risk
- Automatic payment methods show stable revenue performance

## Dashboard Preview
![Dashboard Overview](screenshots/overview.png)

## How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh data and explore insights

