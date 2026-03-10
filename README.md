# student-reality-lab-Olagoke
# Are Subscriptions Becoming Unaffordable?

## Essential Question
Are subscription prices increasing faster than student wages when adjusted for inflation?

## Claim (Hypothesis)
Subscription services are becoming less affordable for students because their prices are increasing faster than both wages and inflation.

## Audience
This project is designed for college students and young adults who use subscription services such as Netflix, Spotify, and other streaming or software platforms and want to understand how these costs affect their budgets.

---

# STAR Draft

## Situation
Many students rely on subscription services for entertainment, productivity, and education. At the same time, students frequently hear about rising inflation and stagnant wages. This raises an important question: are subscription services becoming harder to afford for students over time?

## Task
The viewer should be able to determine whether subscription services have become more expensive relative to wages and inflation, and understand how these costs affect their monthly budget.

## Action
I built an interactive web application that visualizes subscription prices alongside wage growth and inflation. The site allows users to explore the relationship between these variables through interactive charts and calculations.

The project includes:
- A chart comparing subscription prices over time
- A comparison with inflation and wage growth
- A calculator showing how much of a student's income subscriptions consume
- Interactive elements that allow users to toggle between different subscription services

## Result
The data is expected to show that subscription costs have increased significantly over time and may outpace wage growth in certain periods. The key metric reported will be the percentage of monthly student income required to pay for common subscriptions.

---

# Dataset & Provenance

Primary Data Sources:

US Inflation Data  
U.S. Bureau of Labor Statistics (Consumer Price Index)  
https://www.bls.gov/cpi/  
Retrieved: April 2026  
Usage: Public government dataset

Wage Data  
U.S. Bureau of Labor Statistics – Average Hourly Earnings  
https://www.bls.gov/ces/  
Retrieved: April 2026  
Usage: Public government dataset

Subscription Pricing Data  
Historical pricing data for major subscription services collected from:
- Netflix pricing history
- Spotify pricing history
- Public articles and archived pricing pages

Sources include:
- Company pricing announcements
- Archived pricing pages
- Technology news coverage

Usage: Public informational sources used for research.

---

# Data Dictionary

| Column Name | Meaning | Units |
|-------------|--------|------|
| year | Year the data was recorded | Year |
| subscription_price | Monthly cost of a subscription service | USD |
| inflation_rate | Annual inflation rate for that year | Percent |
| avg_hourly_wage | Average hourly wage in the US | USD |
| monthly_income_estimate | Estimated monthly income for a student worker | USD |
| subscription_share_income | Percent of income spent on subscriptions | Percent |

---

# Data Viability Audit

## Missing Values + Weird Fields

Potential issues include:

- Historical subscription prices may not be available for every year.
- Inflation data is annual while subscription prices may change at irregular times.
- Wage data reflects national averages, not specifically student wages.

## Cleaning Plan

Data cleaning steps will include:

- Converting all prices to constant dollars when comparing across years.
- Aligning yearly inflation data with subscription pricing timelines.
- Removing duplicate records or incomplete entries.
- Standardizing currency values to USD.

## What This Dataset Cannot Prove (Limits / Bias)

- The wage data reflects national averages, not specifically student wages.
- Subscription pricing data may vary by country or promotional discounts.
- Individual students may share subscriptions or use family plans.
- The analysis does not capture all possible subscription services.

Because of these limitations, the project focuses on illustrating general trends rather than exact personal spending behavior.

---

# Draft Chart Concept

Chart: Subscription Cost vs Inflation vs Wage Growth

The draft visualization compares the growth of subscription prices against inflation and wage growth over time.

Why this chart answers the question:

- It shows whether subscription prices are rising faster than wages.
- It allows viewers to visually compare economic trends affecting affordability.
