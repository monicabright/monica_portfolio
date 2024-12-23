# **Digital Marketing Analytics: Fresh Cart Ad Spend Analysis**  

## **Project Background**  
Fresh Cart is a leading online grocery store operating in the competitive e-commerce sector. The company relies heavily on digital advertising to drive customer acquisition and sales. With increasing ad spend across multiple platforms, Fresh Cart sought to optimize its ad strategy to ensure maximum ROI and efficiency.  

As a **Data Analyst** at Fresh Cart, I analyzed campaign data from Excel using Power BI to uncover actionable insights that support smarter budget allocation and more effective ad campaigns.  

---

## **Insights and Recommendations**  
This analysis provided insights and actionable recommendations across four key areas:  
- **Platform Effectiveness**: Evaluating the ROI and efficiency of different advertising platforms.  
- **Campaign Optimization**: Identifying high-performing campaigns and opportunities for improvement.  
- **Audience Engagement**: Understanding audience behavior and preferences.  
- **Budget Reallocation**: Suggesting fund redistribution to maximize returns.  

---

## **Data Structure & Initial Checks**  
The dataset consisted of campaign-level data imported from Excel and included approximately **50 rows**.  

### **Key Data Points**:  
- **CampaignID**: Unique identifier for each campaign.  
- **Platform**: Advertising platform (e.g., YouTube, Twitter).  
- **AdDuration**: Duration of the ad campaign.  
- **Cost**: Amount spent on the campaign.  
- **Impressions, Clicks, Conversions**: Key engagement metrics.  
- **ConversionValue**: Revenue generated from conversions.  

### **Data Modeling in Power BI**:  
- A **Date Table** was created using **DAX** to enable time-based analysis.  
- Custom **DAX Measures** calculated KPIs, including:  
  - **Conversion Rate** = `DIVIDE([Conversions], [Clicks], 0)`  
  - **ROAS** = `DIVIDE([ConversionValue], [Cost], 0)`  
  - **Cost per Conversion** = `DIVIDE([Cost], [Conversions], 0)`  
  - **Impression-to-Click Rate** = `DIVIDE([Clicks], [Impressions], 0)`  

These measures provided critical metrics to assess platform performance and supported informed decision-making.

![](https://github.com/monicabright/monica_portfolio/blob/main/Fresh%20cart/Model_Image.png)

---

## **Executive Summary**  
### **Overview of Findings**  
The analysis revealed that **YouTube** was the most cost-effective platform, delivering the highest ROI and conversion efficiency. Conversely, **Google Ads** demonstrated inefficiencies that required reassessment.  

#### **Top Insights**:  
1. **YouTube**: Outstanding ROAS of 1298.84% and the lowest cost per conversion ($2.72).  
2. **Google Ads**: High cost per conversion ($35) and the lowest conversion rate (4.62%).  
3. **Twitter**: Moderate performance, with potential for optimization in ad targeting and content strategy.  

![](https://github.com/monicabright/monica_portfolio/blob/main/Fresh%20cart/roas_performance_by_platform.png) 

---

## **Insights Deep Dive**  

### **Platform Effectiveness**:  
- **YouTube**:  
  - Conversion rate: 6.41%, well above the industry average (1-3%).  
  - Generates significant sales revenue with fewer campaigns.  

- **Google Ads**:  
  - High CPC and the lowest ROAS (180.88%).  

### **Campaign Optimization**:  
- Benchmarked successful YouTube campaigns to guide content strategy.  
- Identified underperforming campaigns on Google Ads and Twitter for refinement.  

### **Audience Engagement**:  
- High engagement levels on YouTube and Twitter indicate opportunities for targeted retargeting campaigns.  

### **Budget Reallocation**:  
- Recommended reallocating budget from Google Ads to YouTube for higher ROI.

![](https://github.com/monicabright/monica_portfolio/blob/main/Fresh%20cart/Campaigns_duration%20-%20Copy.png)

---

## **Recommendations**  
Based on the findings, I recommend:  
1. **Increase Investment in YouTube**: Leverage its high ROAS by running more campaigns or extending durations.  
2. **Optimize Twitter Ads**: Improve targeting and creative content to enhance ROAS.  
3. **Reassess Google Ads Strategy**: Revisit ad creatives, keyword targeting, and landing pages for better performance.  
4. **Implement Retargeting Campaigns**: Across all platforms, re-engage visitors to improve conversion rates.  

---

## **Technical Implementation**  
This project was executed entirely in **Power BI**, with the following steps:  
1. **Data Import**: The dataset was imported directly from Excel.  
2. **Data Transformation**: Cleaned and prepared the data using Power Query.  
3. **DAX Measures**: Created to calculate key metrics like ROAS, Conversion Rate, and Cost per Conversion.  
4. **Visualizations**: Designed interactive dashboards to present findings and enable stakeholder exploration. 
