# AtliQo Telecom Analysis - Power BI

This project was undertaken as part of the November Codebasics Resume Project Challenge.

## Challenge Details
[Challenge Details](https://codebasics.io/challenge/codebasics-resume-project-challenge)

## Live Dashboard
[Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGU1MmYzMzItNWE2NC00NDRmLTljOTItZTU3YmNjMWRlYzE1IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


## Problem Statement

AtliQo, a leading telecom provider in India, launched its 5G plans in May 2022, alongside other telecom providers. Following this launch, the management observed a decline in active users and revenue growth.

To address these issues, AtliQo's business director requested the analytics team to generate a comparison report of key performance indicators (KPIs) for the periods before and after the 5G launch. The goal is to understand the performance differences between these periods and gain insights that will help recover the active user rate and improve other key metrics. Additionally, the management is looking to optimize their internet plans to attract more active users.

**Peter Pandey**, a junior data analyst, has been assigned this task.

## Task

As Peter Pandey, perform the following tasks:

1. **Create a Comparison Report:**
   - Use the provided mock-up as a starting point. Note that the mock-up was created by a business user with limited dashboarding experience, so it's crucial to enhance the representation of insights.

2. **Target Audience:**
   - The dashboard is intended for top-level management. Therefore, it should be self-explanatory and easy to understand.

3. **Generate Additional Insights:**
   - Go beyond the metrics listed in the mock-up to provide relevant insights that support the analysis and decision-making process.

## Project Structure

- **Power BI Dashboard:**
  - A comprehensive Power BI dashboard that includes multiple pages for different analyses:
    - Dashboard Overview
    - Market Share Analysis
    - Revenue & Plan Performance
    - City Comparison Performance

- **Data Sources:**
  - `Dim_city` table: Contains city names and city codes.
  - `Dim_Date` table: Contains month, date, and time period.
  - `Plan` table: Contains plan name, description, data/day, and validity.
  - `Fact_atliq_metrics` table: Contains date, company, AtliQo revenue, active revenue per user (ARPU), active users, and unsubscribed users.
  - `market_share` table: Contains city code, total market value, company, and market share percent.
  - `fact_plan_revenue` table: Contains city, plan, plan revenue, and date.


