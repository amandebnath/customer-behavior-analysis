# Customer Shopping Behavior Analysis Project

## Executive Summary
This project follows a professional corporate workflow to analyze retail customer behavior. By processing raw data in **Python**, performing deep-dive analysis in **PostgreSQL**, and visualizing insights in **Power BI**, the project identifies high-value customer segments and optimized delivery strategies. The final output includes a client-ready presentation and a fully interactive dashboard.

## Objective
The goal is to answer critical business questions regarding:
* Customer demographics and their impact on revenue.
* The effectiveness of current subscription and discount programs.
* Product performance and ranking across different retail categories.

## Data Source
* **Dataset:** Customer Shopping Behavior CSV.
* **Attributes:** 3,900 rows containing Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount, Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Previous Purchases, and Frequency.

## Tech Stack
* **Python:** Data cleaning and Feature Engineering (Pandas, SQL Alchemy).
* **SQL:** Advanced querying in PostgreSQL (Window Functions, CTEs).
* **Power BI:** Data visualization and DAX measures.
* **Gamma AI:** Automated presentation generation.

## Analysis Workflow
* **Python:** Imputed missing ratings using category medians, handled feature engineering (age groups), and converted text frequencies to numeric day counts.
* **SQL:** Segmented customers into New, Returning, and Loyal groups based on purchase history. Analyzed revenue by gender and shipping preference.
* **Power BI:** Built a sleek, interactive dashboard with dynamic slicers to track KPIs like average spend and subscriber distribution.

## Business Recommendations
* **Loyalty Conversion:** Targeted campaigns should focus on the 2,500+ repeat buyers who are not yet subscribers.
* **Shipping Tiers:** Express shipping drives higher spending; recommend incentivizing faster shipping for premium categories.
* **Marketing Focus:** Focus budget on the "Young Adult" segment, as they represent the highest total revenue.

## Preview
| Final Dashboard Preview |
| :--- |
| ![Dashboard Screenshot](screenshots/preview.png) |
