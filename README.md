# 🎧 Spotify Customer Churn Analysis

## 🧠 Project Overview

In this project, we aim to perform customer churn analysis for Spotify users to identify the factors contributing to churn (users leaving the platform).
Tools used for analysis include **Excel**, **Power BI**, and **SQL**.

The goal is to uncover insights into user behavior, churn patterns, and retention opportunities to help Spotify improve user engagement and reduce churn.

---

## 📋 Table of Contents

1. Project Overview
2. Problem Statement
3. Data Source
4. Data Cleaning / Preparation
5. Live Dashboard
6. Dashboard Image
7. Inferences
8. Recommendations
9. Limitations

---

## ❓ Problem Statement

Spotify faces a moderate churn rate among its users. Understanding which user segments are more likely to leave—and why—is crucial to improving retention strategies.

By identifying key drivers of churn such as **listening time**, **device type**, and **subscription plan**, Spotify can take proactive measures to enhance the user experience and increase customer loyalty.

---

## 🗂️ Data Source

* **Domain:** Music Streaming / Customer Analytics
* **Dataset Name:** Spotify_Churn_Data.xlsx
* **Dataset Type:** Excel
* **Dataset Size:** 8,000 customers

### Columns Included:

`User_Id`, `Gender`, `Age`, `Country`, `Subscription_Type`, `Listening_Time`, `Songs_Played_Per_Day`, `Skip_Rate`, `Device_Type`, `Ads_Listened_Per_Week`, `Offline_Listening`, `Is_Churned`

---

## 🧹 Data Cleaning / Preparation

* Removed duplicate records.
* Standardized data types (numeric, text).
* Cleaned inconsistent or missing values.
* Reformatted column names for uniformity.
* Verified logical consistency across churn status and activity fields.

---

## 📊 Live Dashboard

**Excel Dashboard (View Online):**  
[Open Spotify Churn Dashboard](https://1drv.ms/x/c/e493825a3532b2c6/EQTY3PxBcpNBqhDk9wQxzHQBEgXdUtJdhpoLdZg0IKKblg?e=Wtf53r)
---

## 🖼️ Dashboard Image

Below is the visual dashboard created in Excel:

![Spotify Churn Dashboard](<upload your dashboard image or link here>)

---

## 📈 Inferences from the Analysis

### 🔹 Summary

* **Total customers:** 8,000
* **Active users:** 5,929
* **Churned users:** 2,071
* **Overall churn rate:** 25.9%

---

### 🔹 Key Insights

1. **Mobile users show the highest churn**
   The majority of users access Spotify via mobile devices, which also have the highest churn. Improving mobile app performance will have the greatest impact.

2. **Churn is behavior-driven, not demographic**
   Gender and age groups show similar churn trends. Listening behavior (time and skip rate) influences churn more strongly than demographics.

3. **Listening time and skip rate are strong churn predictors**
   Users with **low listening time** or **high skip rates** are more likely to churn. These are key metrics for early churn prediction.

4. **Free users churn more than paid users**
   Subscription type affects churn — **paid users (Duo, Family)** retain better than **Free** or **Student** users.

5. **Country-wise churn variation is minimal**
   Churn rate ranges between **24%–27%**, with **Australia** and **Pakistan** showing slightly higher churn.

---

## 💡 Recommendations

* **Enhance mobile experience:**
  Focus on app speed, stability, and personalized recommendations to improve satisfaction.

* **Encourage Free → Paid conversions:**
  Offer premium trial campaigns or discounts to promote upgrades.

* **Re-engage low-activity users:**
  Send personalized playlists and reminders to users with declining listening time.

* **Use predictive churn analytics:**
  Build an early-warning model using listening time and skip rate as core indicators.

* **Monitor behavioral segments:**
  Track high-risk segments (low listening, high skips) and target them with retention campaigns.

---

## 🚧 Limitations

* The dataset may not include **external behavioral data** such as marketing influence or competitor actions.
* Findings are based on **historical data** and may change with user trends.
* Lack of **real-time tracking** may limit early churn detection accuracy.
* Country-level insights may vary with regional user base size.

---

## 🏁 Conclusion

The overall churn rate of **25.9%** shows moderate risk, primarily influenced by **user engagement behavior** rather than demographics.
Improving **mobile retention**, **engagement frequency**, and **Free-to-Paid conversion** can significantly lower churn and strengthen Spotify’s customer loyalty base.

---

📘 *Project by Yogeshwaran N (2025)*
