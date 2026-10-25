# SCT_DA_4
Exploratory Data Analysis of marketing campaigns, including data cleaning, funnel visualization, channel performance, ROI, and business recommendations.

# Marketing Campaign Analysis — SkillCraft Technology Task 4

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a marketing campaign dataset to evaluate marketing channel performance, analyze the conversion funnel, and identify opportunities for improving advertising budget allocation.

**Objective:** Understand why some marketing channels perform better than others using data analysis and business insights rather than Machine Learning.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Google Colab
- GitHub

## Dataset
The dataset contains 150 synthetic campaign records across five channels:
- Email Marketing
- Google Ads
- LinkedIn Ads
- Instagram Ads
- Facebook Ads

Key columns include campaign date, channel, advertising spend, impressions, clicks, conversions, and revenue.

**Note:** The dataset is synthetic and intended for educational purposes. It does not represent actual SkillCraft Technology business data.

## Project Workflow
1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Prepared numerical and date columns.
4. Calculated CTR, conversion rate, CPC, CPA, ROAS, and ROI.
5. Visualized the marketing conversion funnel.
6. Compared channel-level spending, revenue, and returns.
7. Developed business recommendations based on the results.

## Key Findings
- Email Marketing achieved the highest ROAS at 55.61×.
- Email Marketing also had the highest calculated ROI (5,461.19%) and lowest CPA (1.15 currency units).
- Google Ads generated the highest total revenue (1,534,722.46) and conversions (14,768).
- Instagram Ads and Facebook Ads had the lowest ROAS among the five channels, at 8.49× and 8.30×, respectively.

These findings are based on the synthetic dataset used in this project.

## Business Recommendations
- Test gradual budget increases for Email Marketing.
- Continue evaluating Google Ads because of its high revenue and conversion volume.
- Review targeting and acquisition costs for LinkedIn Ads.
- Test new creatives, audiences, and landing-page improvements for Instagram and Facebook Ads.
- Monitor performance before making major budget changes.

## Project Files
- `SCT_Task4_Marketing_EDA.ipynb` — Python analysis notebook
- `skillcraft_task4_marketing_campaigns.csv` — Dataset
- `Business_Insights_Report.pdf` — Business insights report, if included

## Conclusion
This project demonstrates how EDA and business metrics can support marketing performance analysis and data-driven budget allocation decisions.

**Created as part of the SkillCraft Technology Task 4 project.**
