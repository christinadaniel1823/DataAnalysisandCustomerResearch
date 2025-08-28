# DataAnalysisandCustomerResearch

Chips Category Retail Analytics – Quantium Forage Project
Project Overview

This project demonstrates end-to-end retail analytics conducted as part of Quantium’s Virtual Data Analytics Program on Forage. The objective was to provide actionable insights on the chips category by analyzing customer purchasing behaviour and evaluating store-level initiatives, supporting strategic decision-making for the Category Manager.

Key focus areas included:

Understanding customer segment behaviour and purchase patterns

Deriving insights on pack size and brand preferences

Assessing store trial performance against control stores

Delivering clear, data-driven recommendations for growth

Data Sources

Transaction Data: Detailed sales transactions for chips over a 12-month period.

Customer Purchase Behaviour Data: Demographics, lifestage, and purchasing attributes of customers.

Trial Store Data: Store-level performance metrics for trial initiatives (stores 77, 86, 88).

Analysis Workflow
Task 1 – Customer & Chip Purchasing Behaviour

Merged transaction and customer datasets after cleaning and removing outliers.

Engineered features such as pack size and brand from product names.

Calculated metrics by segment: total sales, units per customer, average price per unit.

Identified high-value segments, including Mainstream – Young Singles/Couples and Budget – Older Families.

Provided targeted recommendations for promotions, merchandising, and pack size optimization.

Task 2 – Store Trial Evaluation

Selected control stores using Pearson correlation and magnitude distance metrics for comparison.

Analyzed trial store performance against controls on total sales, customer count, and average transactions per customer.

Applied statistical tests to evaluate significance of performance differences.

Visualized trends and highlighted drivers of sales growth at store level.

Generated store-specific recommendations to inform strategic rollouts.

Task 3 – Reporting & Insights Presentation

Developed a client-ready summary report with visualizations and key findings.

Focused on delivering commercially actionable insights with minimal jargon.

Presented recommendations tailored to both customer segments and store-level strategies.

Technical Skills & Tools

Data Cleaning & Transformation: R (data.table, dplyr, readr)

Statistical Analysis: t-tests, correlations, magnitude distance

Feature Engineering: Pack size, brand extraction, segment metrics

Visualization: ggplot2, ggmosaic for clear stakeholder communication

Reporting: R Markdown, PDF export for professional delivery

Key Takeaways

Customer segment analysis drives targeted marketing and merchandising strategies.

Store trials provide quantifiable insights into the effectiveness of promotions and store-level initiatives.

Data-driven recommendations enable strategic growth opportunities for the chips category.

Demonstrates ability to bridge technical analytics with actionable business insights.

Project Repository Contents

QVI_transaction_data.csv – Raw sales transaction data

QVI_purchase_behaviour.csv – Customer demographic and purchase data

QVI_data_cleaned.R – Data cleaning and feature engineering scripts

Store_Trial_Analysis.Rmd – Full R Markdown report with visualizations and insights

README.md – Project overview and methodology (this file)

This project showcases applied retail analytics and strategic insights development using real-world datasets as part of Quantium’s Forage Data Analytics program.
