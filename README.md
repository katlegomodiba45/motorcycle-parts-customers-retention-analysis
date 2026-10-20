# Motorcycle Parts - Customer Retention & Churn Analysis
> Part 3 of R115M Wholesale Audit Series | Author: Katlego Modiba

## Business Problem
68% of customers (816 out of 1,200) buy once and never return. Company losing an estimated R1.2M/year in repeat revenue.

## Data
- 5,000 orders from Jan 2024 - Jun 2025
- 1,200 unique customers
- Fields: customer_id, warehouse, region, product_line, order_value

## Methodology
1. Segmented customers: One-time (1 order), Repeat (2 orders), Loyal (3+ orders)
2. Calculated churn rate by warehouse
3. Linked churn to fee leakage found in Audit #1
4. Analyzed retention by region and product line

## Key Findings
- One-time buyers: 68% - HIGH RISK
- Warehouse B churns 2.3x more than A & C (correlates with 7.5% fee vs 3.2% benchmark)
- Most loyal region: Gauteng - 45% repeat rate
- Best product for retention: Engine Parts - 40% repeat vs Electrical 18%

## Business Impact & Recommendation
1. Fix Warehouse B fee structure (already flagged R3M leakage in Audit #1)
2. Launch re-engagement campaign: 10% discount to 816 one-time buyers
3. Projected outcome: Retention 32% -> 50%, saving R1.2M/year

## Tools
Python, Pandas, Cohort Analysis

## Full Series
1. Fee Leakage Audit: https://github.com/katlegomodiba45/motorcycle-parts-revenue-analysis-fee-leakage-audit
2. Sales Performance Dashboard
3. This Repo - Customer Retention
