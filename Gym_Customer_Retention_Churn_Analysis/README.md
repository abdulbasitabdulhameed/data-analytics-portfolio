# Gym Customer Retention & Churn Analysis

## Overview

This project analyses gym membership data to identify **where customer churn is concentrated, which member characteristics and behaviours are associated with higher churn, and where retention efforts should be prioritised.**

The analysis transforms membership and engagement data into actionable insights for improving customer retention.

## Business Problem

The gym is experiencing customer churn and needs to understand which members are most at risk of leaving.

The analysis focuses on three key questions:

* **Who is churning?**
* **What behaviours are associated with churn?**
* **Where should the business focus its retention efforts?**

## About the Dataset

The analysis uses the **Gym Customers Features and Churn** dataset from Kaggle.

The dataset contains member demographics, contract information, attendance behaviour, group participation, referral and partnership status, additional charges, and churn status.

These fields allow the analysis to examine customer characteristics and engagement patterns in relation to churn.

## Business Questions

1. What is the current churn rate?
2. Which age groups have the highest churn?
3. Does contract timing relate to higher churn?
4. Is lower attendance associated with higher churn?
5. Do members who participate in group visits show lower churn?
6. Do referred members show lower churn?
7. Do partner members show lower churn?

## Approach

The data was cleaned and prepared using **Power Query**.

**DAX** was used to create analytical measures, churn rate calculations, and customer groups required for the analysis.

The analysis compared churn rates across:

* Age groups
* Contract end periods
* Attendance levels
* Group visit participation
* Referral status
* Partnership status

The results were presented in an interactive **Power BI dashboard** designed to move from the overall churn situation to the customer segments and behaviours associated with higher churn.

## Dashboard

<img width="960" height="538" alt="GYM CUSTOMER RETENTION   CHURN ANALYSIS" src="https://github.com/user-attachments/assets/9511a745-f9c0-4be5-a2be-bddf5ea637cb" />

The dashboard includes:

* Total Members
* Active Members
* Churned Members
* Churn Rate
* Average Charges
* Average Attendance
* Churn Rate by Age Group
* Churn Rate by Contract End
* Churn Rate by Attendance Level
* Churn Rate by Group Visits
* Churn Rate by Referral
* Churn Rate by Partnership

A gender slicer allows the analysis to be viewed separately for male and female members.

## Key Findings

### Younger Members Showed the Highest Churn

Members aged **18 to 24 had a 66% churn rate**, compared with 36% for ages 25 to 29, 12% for ages 30 to 34, and 2% for ages 35 to 41.

The 18 to 24 segment represents the clearest age based retention risk in the dataset.

### Churn Increased Near Contract Expiry

Members with **0 to 2 months remaining on their contract had a 42% churn rate**.

This fell to 13% for members with 3 to 5 months remaining, 11% for 6 to 8 months, and 2% for 9+ months.

This identifies the period approaching contract expiry as an important retention window.

### Low Attendance Was Associated With Higher Churn

Members in the **Low attendance group had a 40% churn rate**, compared with 8% among Medium attendance members.

This suggests that low recent engagement may be a useful early warning signal for potential churn.

### Group Participation Was Associated With Lower Churn

Members who did not participate in group visits had a **33% churn rate**, compared with 17% among members who participated in group visits.

This indicates a strong difference in churn between members with and without group participation.

### Referred Members Had Lower Churn

**Non referred members had a 31% churn rate**, compared with 16% among referred members.

Referred members therefore showed substantially lower churn in this dataset.

### Partner Members Had Lower Churn

Partner members had a **19% churn rate**, compared with 33% among corporate members.

This indicates a notable difference in retention between the two membership groups.

## Recommendations

Based on the findings, the gym should:

* **Prioritise younger members**, particularly the 18 to 24 segment, with targeted retention initiatives.
* **Start renewal engagement before contract expiry**, particularly for members entering their final two months.
* **Monitor low attendance** and proactively engage members showing weak or declining participation.
* **Encourage group participation** through classes and community activities where appropriate.
* **Strengthen referral programmes** while monitoring the retention quality of referred members.
* **Investigate higher churn among corporate members** to understand whether membership structure, engagement, or contract differences contribute to the gap.

## Business Impact

The analysis identifies specific customer segments and behaviours that can help the gym move from broad retention efforts toward more targeted interventions.

The strongest churn signals identified were:

* **18 to 24 age group → 66% churn**
* **0 to 2 months remaining → 42% churn**
* **Low attendance → 40% churn**

These segments provide clear starting points for targeted retention campaigns and further investigation.

## Tools

**Power BI | Power Query | DAX**

## Skills Demonstrated

* Customer churn analysis
* Business problem framing
* Data cleaning and transformation
* KPI development
* Customer segmentation
* DAX
* Data visualization
* Dashboard design
* Insight generation
* Business recommendations

## Power BI Report

https://drive.google.com/file/d/1tDTkXGMtxFCWYyoz__SRh8FWKno0owf1/view?usp=sharing
