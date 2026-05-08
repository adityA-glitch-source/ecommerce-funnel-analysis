# E-Commerce Funnel Analysis

## Overview
End-to-end funnel analysis of 110M+ e-commerce events from a multi-category store (Oct-Nov 2019) using Python and Power BI.

## Key Insights
- Only 5.04% of viewers convert to purchase
- 89.2% drop-off between View and Cart stage
- November shows pre-holiday browsing behavior
- View to Cart tripled (5.32% to 12.22%)
- Cart to Purchase dropped 58% (83.25% to 35.17%)
- Electronics leads conversion at 5.41%
- Apparel has biggest opportunity - 209K viewers but only 0.97% conversion
- Apple dominates revenue at $24M vs Samsung at $10M
- Sunday is peak purchase day

## Tech Stack
- Python (pandas, matplotlib, seaborn)
- Power BI Desktop
- Jupyter Notebook

## Dataset
https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store

## Project Structure
- 01_data_loading.ipynb - Data loading, sampling and cleaning
- 02_funnel_analysis.ipynb - Funnel construction and drop-off rates
- 03_deep_dive.ipynb - Category, revenue and brand analysis
- 04_portfolio_summary.ipynb - Master dashboard and key insights

## How to Run
1. Download dataset from Kaggle link above
2. Place CSV files in the same folder as notebooks
3. Run notebooks in order 01 to 04
4. Open Ecommerce_Funnel_Analysis.pbix in Power BI Desktop

## Key Metrics Summary
| Metric | Value |
|--------|-------|
| Total Users | 2,657,873 |
| Overall Conversion | 5.04% |
| View to Cart Rate | 10.77% |
| Cart to Purchase Rate | 46.79% |
| Top Category | Electronics (5.41%) |
| Top Brand by Revenue | Apple ($24M) |
