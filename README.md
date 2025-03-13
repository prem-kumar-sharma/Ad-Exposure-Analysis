# 📊 Advertisement Impact Analysis - Night Owls I4 Project


![image](https://github.com/user-attachments/assets/366fd270-24ba-4f75-86c2-4d415f890dd0)


![image](https://github.com/user-attachments/assets/c7ec343f-12d0-4d68-968b-5fa31766aa36)


## 📌 Overview
This project analyzes how repeated advertisement exposures impact **Click-Through Rate (CTR), Conversion Rate, and Purchase Likelihood**. The goal is to determine the **optimal number of ad exposures** that maximize conversions while avoiding ad fatigue, using real-world online advertising data.

## 🎯 Objectives
- Identify the relationship between ad exposure frequency and consumer engagement.
- Determine the **optimal number of ad exposures** before engagement stagnates.
- Assess the effectiveness of **different campaign types & channels**.
- Provide **data-driven recommendations** for budget allocation.

## 📂 Dataset
The dataset consists of records from various digital marketing campaigns, capturing:
- **Campaign Details**: Type (Awareness, Retention, Conversion, Consideration), Platform, Tool.
- **Ad Spend & Exposure**: Budget, Channel (PPC, Social Media, Email, SEO, Referral), Estimated Exposures.
- **Engagement Metrics**: CTR, Conversion Rate, Website Visits, Social Shares.
- **User Demographics**: Age, Gender, Income.
- **User Behavior**: Email Opens, Clicks, Purchases, Loyalty Points.

## 🔍 Key Constraints & Solutions
| **Constraint**                                  | **Solution**  |
|-------------------------------------------------|--------------|
| No direct ad exposure count                     | Derived from engagement metrics (Website Visits, Email Opens, Clicks, Social Shares). |
| No time frame for exposure frequency            | Grouped into **Short-Term (1-3 Days), Medium-Term (1-2 Weeks), Long-Term (3+ Weeks).** |
| Limited user-level insights                     | Segmented users into **First-Time Viewers (Lowest 10%) vs. Repeated Viewers.** |
| Risk of ad fatigue                              | Identified stagnation via **trend analysis** on CTR & Conversion Rates. |

## ⚙️ Methodology
1. **Data Preprocessing & Cleaning**: Standardized campaign types, handled missing values.
2. **Feature Engineering**: Created ad exposure metrics, viewer types, and exposure duration.
3. **Exploratory Data Analysis (EDA)**: Used pivot tables & visualizations to assess trends.
4. **Trend Analysis**: Identified **optimal ad exposures & ad fatigue effects**.
5. **Business Recommendations**: Provided **budget allocation strategies based on findings**.

## 📊 Results & Key Findings
- **Best Ad Exposure Range**: **5-20 exposures** within **1-2 weeks** resulted in the highest engagement.
- **Ad Fatigue**: **100+ exposures** led to diminishing returns.
- **Best Performing Campaigns**:
  - 🔹 **Highest Conversion Rate** → **Consideration Campaigns**.
  - 🔹 **Highest CTR** → **Retention Campaigns**.
- **Best Performing Channels**:
  - 🔹 **Highest CTR** → **PPC (Pay-Per-Click)**.
  - 🔹 **Highest Conversion Rate** → **Social Media**.
- **Ad Spend Efficiency**: The **$1K-$5K** budget range maximized CTR & Conversion Rates.
- **Viewer Type Analysis**:
  - 🔹 **First-Time Viewers** performed better than **Repeated Viewers**.
  - 🔹 **Retargeting did not significantly improve conversions.**

## 📢 Recommendations for Advertisers
✔ **Optimize ad exposure**: Keep it within **5-20 times over 1-2 weeks**.  
✔ **Avoid excessive retargeting**: Focus on attracting new users instead.  
✔ **Allocate budget to high-performing campaign types & channels**.  
✔ **Limit ad exposures beyond 100 per user** to prevent ad fatigue.  
✔ **Invest in PPC & Social Media campaigns** for maximum impact.  

