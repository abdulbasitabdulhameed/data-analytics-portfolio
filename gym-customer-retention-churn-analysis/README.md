# Gym Customer Retention & Churn Analysis

## Overview

This project analyses gym membership data to identify where customer churn is concentrated, which member characteristics and behaviours are associated with higher churn, and where retention efforts should be prioritised.

## Business Problem

The gym needs to understand which members are most likely to churn and which factors are associated with customer retention.

The analysis focuses on:

* Who is churning?
* Which behaviours are associated with higher churn?
* Where should retention efforts be prioritised?

## About the Dataset

The analysis uses the **Gym Customers Features and Churn** dataset from Kaggle.

The dataset contains member demographics, contract information, attendance, group participation, referral and partnership status, additional charges, and churn status.

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

**DAX** was used to create measures, calculate churn rates, and create customer groups.

Churn rates were compared across age, contract timing, attendance, group visits, referral status, and partnership status.

## Dashboard

<img width="960" height="538" alt="GYM CUSTOMER RETENTION   CHURN ANALYSIS" src="https://github.com/user-attachments/assets/1e4c845f-d2b9-4fea-83ca-bb0271eed473" />

The dashboard provides an overview of membership and churn performance, with a gender slicer for additional analysis.

## Key Findings

* **Age:** Members aged 18 to 24 had the highest churn rate at **66%**, compared with 36% for ages 25 to 29, 12% for ages 30 to 34, and 2% for ages 35 to 41.

* **Contract timing:** Members with 0 to 2 months remaining had a **42% churn rate**, compared with 13% for 3 to 5 months, 11% for 6 to 8 months, and 2% for 9+ months.

* **Attendance:** Members in the Low attendance group had a **40% churn rate**, compared with 8% among Medium attendance members.

* **Group visits:** Members without group visits had a **33% churn rate**, compared with 17% among members with group visits.

* **Referral:** Non referred members had a **31% churn rate**, compared with 16% among referred members.

* **Partnership:** Partner members had a **19% churn rate**, compared with 33% among corporate members.

## Recommendations

* Prioritise retention efforts for members aged 18 to 24.
* Engage members before their contracts enter the final two months.
* Monitor members with low attendance and intervene early.
* Encourage group participation as part of member engagement initiatives.
* Strengthen referral programmes while monitoring member retention.
* Investigate the higher churn rate among corporate members.

## Business Impact

The analysis highlights three key churn signals:

* **Age 18 to 24: 66% churn**
* **0 to 2 months remaining: 42% churn**
* **Low attendance: 40% churn**

These findings provide clear areas for targeted retention efforts.

## Tools

**Power BI | Power Query | DAX**

## Power BI Report

https://drive.google.com/file/d/1tDTkXGMtxFCWYyoz__SRh8FWKno0owf1/view?usp=sharing
