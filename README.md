# Marketing Campaign Analysis for FreshCart (January 2023 – August 2023)

## Project Background
FreshCart is an online grocery store operating in the e-commerce industry for several years. The company’s business model relies heavily on online advertising across multiple platforms to drive customer acquisition and retention. Key business metrics such as conversion rates, return on ad spend (ROAS), and cost per conversion guide its advertising strategies. This project provides insights and recommendations for optimizing FreshCart’s ad spend based on historical campaign data.

Insights and recommendations are provided on the following key areas:
- Platform Effectiveness
- Cost Efficiency
- Return on Ad Spend (ROAS)
- Campaign Optimization

An interactive Power BI dashboard used to report and explore sales trends can be found [here]( https://app.powerbi.com/view?r=eyJrIjoiY2Q1YWJiMTItNjgwZS00NmU0LWI5NmMtNmY1NDY2MmUyNmZjIiwidCI6IjI5OTkwODdiLTFkYTUtNDIzNC04Mjg4LTk4YjFjNGMxZGNhZSJ9)

---

## Data Description
The marketing team provided an Excel file containing FreshCart ad campaign data. The primary database structure consists of one main table (Ad Campaign Data) with approximately 50 records. 
Data integrity was validated by checking for null values and duplicates, ensuring the data was clean and accurate. Additionally, data types for fields such as dates, numeric values, and text were standardized to maintain consistency across the dataset. To enhance data analysis, calculated columns and measures were created using DAX in Power BI, enabling more insightful reporting and decision-making.
A data model was created in Power BI, integrating the Ad Campaign Data with the Date Table to facilitate time-based analytics.
![](https://github.com/monicabright/monica_portfolio/blob/main/Fresh%20cart/Model_Image.png)

---

## Executive Summary
### Overview of Findings
FreshCart’s advertising campaigns have shown varying levels of performance across platforms. The key findings include:
1. **YouTube** emerged as the most effective platform due to its high conversion rates, low cost per conversion, and impressive ROAS.
2. **Google Ads** was identified as the least cost-efficient platform, with the highest cost per conversion and lowest ROAS.
3. Opportunities exist to optimize ad spend on Twitter and improve overall campaign targeting.

### Key Visualization
The Power BI dashboard provides an overview of platform performance, including total spend, revenue, conversion rates, and ROAS.
![](https://github.com/monicabright/monica_portfolio/blob/main/Fresh%20cart/whole%20dashboard.png)

---

## Insights Deep Dive

### Platform Effectiveness
-  **YouTube’s** conversion rate is 6.41%, exceeding industry averages (1-3%).
-  **Twitter’s** conversion rate is 6.79%, making it competitive but less cost-effective than YouTube.
-  **Google Ads** has the lowest conversion rate (4.62%), indicating underperformance.
-  ** Facebook and Instagram** show moderate performance, with room for optimization.

### Cost Efficiency
-  **YouTube’s** cost per conversion is $2.72, the lowest among platforms.
-  **Google Ads** cost per conversion is $35, the highest.
-  **Twitter’s** cost per conversion ($14.21) suggests potential for cost optimization.
-  ** Facebook and Instagram** have moderate costs per conversion.

### Return on Ad Spend (ROAS)
- **YouTube’s** ROAS is 1298.84%, the highest among platforms.
- **Twitter’s** ROAS is 420.18%, indicating good returns but room for improvement.
- **Google Ads** ROAS is 180.88%, the lowest.
- ** Facebook and Instagram** ROAS are moderate, requiring further analysis.

### Campaign Optimization
- **YouTube’s** fewer campaigns (9 vs. 12 on Twitter) and shorter durations deliver superior results.
- **Twitter’s** higher number of campaigns does not translate into proportional revenue.
- **Google Ads** high spend yields relatively low revenue, requiring a reassessment of strategy.
-  ** Facebook and Instagram** campaigns perform consistently but lack standout metrics.

---

## Recommendations
Based on the insights, the following recommendations are proposed:

### YouTube
1. Increase Ad spend due to high ROAS and low cost per conversion.
2. Extend successful campaigns and replicate top-performing strategies.

### Twitter
1. Optimize targeting and creative content to reduce costs.
2. Refine campaign strategy based on performance analytics.

### Google Ads
1. Reassess keywords, ad creatives, and landing pages to improve performance.
2. Focus on reducing cost per conversion and increasing ROAS.

### Overall Recommendations
1. Implement retargeting campaigns across platforms to enhance conversions.
2. Allocate budget strategically, prioritizing high-performing platforms.

---

## Assumptions and Caveats
1. Missing data for certain campaigns was excluded from the analysis.
2. Conversion values were assumed accurate based on provided data.
3. Platform performance may vary by season; this analysis reflects historical trends.

---

This comprehensive analysis equips FreshCart with actionable insights to optimize its advertising strategy, reduce costs, and maximize returns on ad spend.
