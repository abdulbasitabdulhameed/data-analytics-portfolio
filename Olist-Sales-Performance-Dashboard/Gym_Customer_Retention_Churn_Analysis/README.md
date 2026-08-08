# Gym Customer Retention & Churn Analysis

## Overview

A Power BI analysis focused on understanding gym member churn, identifying the customer groups and behaviours associated with higher churn, and highlighting opportunities for improving customer retention.

The analysis moves from the overall churn problem to specific customer segments and engagement patterns that can support targeted retention strategies.

## Business Problem

The gym needed to understand:

- How serious is the current churn problem?
- Which members are most likely to churn?
- Which customer behaviours are associated with higher churn?
- Where should retention efforts be focused?

## Why This Dataset?

The Gym Customers Features and Churn dataset was selected because it combines demographic, membership, contract, attendance, engagement, referral, partnership and churn information.

This made it suitable for investigating not only how many members churned, but also which customer characteristics and behaviours were associated with churn.

**Dataset:** Gym Customers Features and Churn  
**Source:** Kaggle

## Business Questions

1. What is the current churn rate?
2. Which age groups have the highest churn?
3. Does contract expiry relate to higher churn?
4. Is lower attendance associated with higher churn?
5. Do members who participate in group visits show lower churn?
6. Do referred members show lower churn?
7. Do partner members show lower churn?

## Approach

The data was prepared and analysed using Power BI.

**Power Query**
- Cleaned and prepared the dataset
- Reviewed data types
- Prepared categorical fields
- Created groups for age, contract timing and attendance

**DAX**
- Created KPI measures
- Calculated churn rate
- Created customer segments
- Compared churn rates across different customer groups

**Power BI**
- Built an interactive dashboard
- Used KPI cards to provide an executive overview
- Used comparison charts to identify differences in churn
- Added a gender slicer for interactive analysis

## Dashboard

<img width="960" height="538" alt="GYM CUSTOMER RETENTION   CHURN ANALYSIS" src="https://github.com/user-attachments/assets/8511b01c-139b-42b8-b567-85fb0b4a2f64" />


## Key Findings

### 1. Younger Members Showed the Highest Churn

Members aged **18 to 24 had a 66% churn rate**, compared with 36% for ages 25 to 29, 12% for ages 30 to 34, and 2% for ages 35 to 41.

This makes the youngest age group the clearest age based retention risk in the dataset.

### 2. Churn Increased Sharply Near Contract Expiry

Members with **0 to 2 months remaining on their contract had a 42% churn rate**.

This dropped to 13% for members with 3 to 5 months remaining, 11% for 6 to 8 months, and 2% for 9+ months.

This suggests that the period approaching contract expiry is an important retention window.

### 3. Low Attendance Was Strongly Associated With Churn

Members in the **Low attendance group had a 40% churn rate**, compared with only 8% among Medium attendance members.

This indicates that low recent engagement may be a useful early warning signal for potential churn.

### 4. Group Participation Was Associated With Lower Churn

Members who did not participate in group visits had a **33% churn rate**, compared with 17% among members who participated in group visits.

This suggests that members who engage in group activities may have stronger retention.

### 5. Referred Members Had Lower Churn

**Non referred members had a 31% churn rate**, compared with 16% among referred members.

This suggests that referred customers may demonstrate stronger retention behaviour than non referred customers.

### 6. Partner Members Had Lower Churn Than Corporate Members

Partner members had a **19% churn rate**, compared with 33% among corporate members.

This difference suggests that partnership type may be relevant when evaluating retention performance.

## Recommendations

Based on the findings, the gym should:

1. **Prioritise younger members**, particularly the 18 to 24 segment, with targeted engagement and retention initiatives.

2. **Start renewal campaigns before contract expiry**, particularly for members entering their final 2 months.

3. **Monitor declining attendance** and proactively engage members showing low or falling attendance.

4. **Encourage group participation** through classes and community activities where these activities are associated with stronger retention.

5. **Strengthen referral programmes** while continuing to monitor the retention quality of referred customers.

6. **Investigate higher churn among corporate members** to understand whether differences in membership structure, engagement or contract terms are contributing to the gap.

## Business Impact

The analysis identifies clear customer segments and behaviours that can help the gym move from broad retention efforts toward more targeted interventions.

The strongest signals identified were:

**Age 18 to 24 → 66% churn**  
**0 to 2 months remaining → 42% churn**  
**Low attendance → 40% churn**

These segments provide practical starting points for retention campaigns and further investigation.

## Tools

- Power BI
- Power Query
- DAX

## Skills Demonstrated

- Customer churn analysis
- Business problem framing
- Data cleaning and transformation
- KPI development
- Customer segmentation
- DAX
- Data visualization
- Dashboard design
- Insight generation
- Business recommendations

## Power BI Report

https://drive.google.com/file/d/1tDTkXGMtxFCWYyoz__SRh8FWKno0owf1/view?usp=sharing

## Conclusion

This project demonstrates how customer data can be transformed into a business focused churn analysis.

Rather than simply reporting the number of customers who left, the analysis identifies where churn is concentrated and highlights customer characteristics and behaviours that can inform targeted retention strategies.
