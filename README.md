# SCT_DA_4 — Marketing Campaign EDA

## Internship
SkillCraft Technology — Data Analyst Internship

## Task 04 — Business Insights Report (EDA)

### Objective
Perform Exploratory Data Analysis (EDA) on a marketing campaign dataset to understand the marketing funnel, evaluate channel performance, and recommend which marketing channels should receive more budget based on ROI.

## Dataset
The dataset contains marketing campaign information including:

- Campaign ID
- Marketing Channel
- Region
- Campaign Type
- Ad Spend
- Impressions
- Clicks
- Leads
- Conversions
- Revenue

## Data Cleaning
The dataset was cleaned using Python and Pandas.

Steps performed:
- Identified missing values
- Handled missing categorical values using mode
- Handled missing numerical values using median
- Removed duplicate records
- Standardized text values
- Verified the cleaned dataset

The original dataset contained 505 records. After removing 5 duplicate records, 500 records remained.

## Exploratory Data Analysis

The analysis focused on:

- Marketing funnel performance
- Click-through rate (CTR)
- Lead conversion rate
- Conversion rate
- Revenue by marketing channel
- Advertising spend by channel
- ROI by marketing channel
- ROAS by marketing channel

### Marketing Funnel

The marketing funnel was analyzed as:

**Impressions → Clicks → Leads → Conversions**

## ROI Analysis

ROI was calculated using:

**ROI = ((Revenue - Ad Spend) / Ad Spend) × 100**

The analysis showed that:

- Email had the highest ROI at approximately 116.76%.
- Google Ads had the second-highest ROI at approximately 106.04%.
- Instagram Ads generated approximately 51.93% ROI.
- Social Media generated approximately 40.65% ROI.
- YouTube Ads generated approximately 36.15% ROI.
- Facebook Ads generated approximately -1.15% ROI.

## Business Recommendations

Based on the analysis:

- **Increase budget:** Email and Google Ads
- **Maintain and optimize:** Instagram Ads and Social Media
- **Optimize before increasing significantly:** YouTube Ads
- **Review and potentially reduce:** Facebook Ads

The recommendations are based primarily on ROI and supported by funnel and conversion performance.

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- Exploratory Data Analysis

## Project Files

- `SCT_DA_4_Marketing_EDA.ipynb` — EDA notebook
- `SCT_DA_4_Marketing_Campaign_Cleaned.csv` — Cleaned dataset
- `SCT_DA_4_Business_Insights_Report.pdf` — One-page business insights report
- `SCT_DA_4_ROI_Chart.png` — ROI comparison visualization
