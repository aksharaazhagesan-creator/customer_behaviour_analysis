# Customer Behavior Analysis

## 1. Overview
This project analyzes customer shopping behavior to identify purchasing patterns, revenue trends, and customer preferences using PostgreSQL and Power BI.

The goal is to transform raw customer shopping data into meaningful insights that can support data-driven business decisions.

## 2. Dataset
The dataset contains customer shopping information, including:
- Customer ID, age, gender, and age group
- Products purchased and product categories
- Purchase amounts and locations
- Subscription status and discount usage
- Shipping type, payment method, and purchase frequency
- Customer ratings and previous purchases

## 3. Tools & Technologies
- **PostgreSQL:** Data storage, querying, and analysis
- **SQL:** Aggregations, filtering, grouping, and business analysis
- **Power BI:** Dashboard development and data visualization
- **GitHub:** Project documentation and version control

## 4. Project Workflow
1. Loaded the customer shopping dataset into PostgreSQL.
2. Explored the dataset and identified relevant customer and purchase attributes.
3. Wrote SQL queries to investigate customer behavior and revenue trends.
4. Connected the dataset to Power BI.
5. Created visualizations to communicate key findings.
6. Documented the analysis and results.

## 5. Business Questions
The analysis explores questions such as:
- What is the revenue contribution of each age group?
- Which product categories generate the most revenue?
- How do purchasing patterns differ by gender?
- Do customers who use discounts continue to make substantial purchases?
- How does subscription status relate to repeat purchasing?
- Which customer segments contribute most to sales?

## 6. Dashboard
The Power BI dashboard presents customer behavior and revenue metrics through interactive visualizations.

**Dashboard Preview:**  
Add your dashboard screenshots to the `screenshots/` folder and embed them here.

Example:

`![Customer Behavior Dashboard](screenshots/dashboard.png)`

## 7. Key Results
Add the actual findings from your SQL analysis and Power BI dashboard here.

Examples of findings to report:
- Highest-revenue age group
- Best-performing product category
- Revenue distribution across customer segments
- Differences between subscribed and unsubscribed customers

Only include results verified by your analysis.

## 8. Repository Structure

```text
customer-behavior-analysis/
├── README.md
├── customer_behavior_analysis_queries.sql
├── screenshots/
│   └── dashboard.png
└── powerbi/
    └── customer_behavior.pbix
```

The Power BI file and screenshots should be included when available.

## 9. How to Run
1. Install PostgreSQL and open pgAdmin.
2. Create a database for the project.
3. Import the customer shopping dataset into a table named `customers`.
4. Open `customer_behavior_analysis_queries.sql`.
5. Execute the queries in PostgreSQL.
6. Open the Power BI report, if the `.pbix` file is available.

## 10. Conclusion
This project demonstrates how SQL-based analysis and business intelligence tools can be used to explore customer purchasing behavior, identify revenue patterns, and communicate findings through visualizations.

