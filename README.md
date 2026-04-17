# 📊 Adventure Works Sales Analysis (2024–2026)

## 🔍 Project Overview

This project presents a comprehensive end-to-end analysis of the Adventure Works dataset, focusing on identifying key revenue drivers, customer purchasing behavior, and product performance.

The analysis is designed to move beyond basic reporting and provide **actionable business insights** by combining data cleaning, transformation, modeling, and visualization techniques.

The primary goal is to understand **which products, customer segments, and attributes contribute the most to revenue**, and how the business can improve its current **11% growth rate**.

## 🎯 Business Problem

* Why are certain product models (like Road bikes) generating significantly higher revenue?
* Which customer segments contribute the most to total sales?
* How can the company optimize marketing and inventory strategies?

## 🎯 Objectives

* Identify top-performing product models and revenue contributors
* Analyze customer demographics (Marital Status, Education, Occupation)
* Track key KPIs such as Sales, Orders, and Growth Rate
* Understand product preferences based on attributes like Color
* Provide business recommendations for revenue growth
  
## 📁 Data Sources

* Adventure Works Retail Dataset
* Tables Used: Sales, Customers, Products, Territories
* Time Period: 2024 – 2026
* Data Volume: 18,000+ records

## 🧹 Data Cleaning (Power Query)

To ensure high-quality data, the following preprocessing steps were performed:

* Standardized categorical values

  * Gender → M/F → Male/Female
  * Marital Status → M/S → Married/Single
  * Home Ownership → Y/N → Yes/No

* Handled missing values

  * Product Color null values replaced with **"Black"**

* Data type corrections

  * Price & Cost → Currency
  * Product Size → Text
  * Date columns → Proper Date format

* Applied **Trim & Clean** functions

  * Removed unwanted spaces and special characters

## 🔄 Data Transformation

* Created **Age column** from Birth Date
* Derived **Monthly Salary** from Annual Income
* Built a **Calendar Table** using DAX (Year, Month, Quarter)
* Implemented **Star Schema Data Model**

  * Sales → Fact Table
  * Customers, Products, Territories → Dimension Tables

## 📊 Dashboard & Visualization Details

### KPI Cards

* Total Sales → **$39M**
* Total Orders → **18K**
* Max Sale Value → **$17.89K**
* Growth Rate → **11%**

### 📊 Bar Chart

**The chart shows a premium-driven trend, where Road-150 ($10.9K) leads while most products remain below $3K, indicating skewed revenue distribution.**

### 📊 Funnel Chart

**Black and Red colors contribute the majority of sales**, while other colors show a steep decline, highlighting strong customer preference concentration.

### 📊 Pie Chart

Customers with a **Bachelor’s degree contribute ~$11.83M**, making them the largest and most valuable customer segment.

### 📊 Column Chart

**Married customers generate ~$21M**, contributing more than 50% of total revenue, indicating higher purchasing power.

### 📊 Treemap

The occupation chart shows Professionals ($11.18M) and Skilled Manual ($10.67M) as top contributors, while Clerical, Management, and Manual segments contribute comparatively less, indicating higher revenue from skilled and professional workers

### 📊 KPI Cards

With **18K orders generating $39M**, the average order value is approximately **$2.1K**, supported by high-value transactions up to **$17.89K**.

### 📊Line Chart

With a steady **11% growth rate**, projected revenue is expected to exceed **$43M**, assuming current trends continue.

### 📊 Scatter Plot

Customers with a **moderate number of children show higher spending**, indicating an optimal target group rather than a linear relationship.


## 🧠 Key Insights

* Revenue is heavily driven by **premium products**, especially Road-150
* Customer preference is highly concentrated in **Black and Red colors**
* **Married Professionals** form the most profitable customer segment
* Education level directly impacts purchasing power
* Business follows a **high-value, low-volume sales model**


## 📈 Analytics Approach

* **Descriptive:** Achieved $39M sales with 18K orders
* **Diagnostic:** Revenue driven by Professionals & Married customers
* **Predictive:** Expected ~$43M revenue based on 11% growth
* **Prescriptive:** Focus on high-income segments and premium products


## 📌 Final Conclusion

This analysis clearly shows that Adventure Works operates with a **premium-driven business model**, where revenue is concentrated around high-value products and a specific customer segment.

The **Road-150 model**, along with strong demand for **Black and Red colors**, forms the core of sales performance.

From a customer perspective, **Married Professionals with Bachelor’s degrees** contribute the majority of revenue, indicating that income stability and education significantly influence purchasing behavior.

The presence of high-value transactions (up to **$17.89K**) further confirms that the business relies on **quality over quantity**, focusing on fewer but higher-value orders.

However, the business also faces **concentration risk**, as it depends heavily on:

* A single product category
* Limited color preferences
* A narrow customer segment

To sustain and improve growth, the company should:

* Expand product variety beyond Road models
* Introduce new color options strategically
* Target additional customer segments while retaining high-value customers

With these improvements, the company is well-positioned to surpass **$43M in revenue**, ensuring long-term scalability and stability.

## 🛠️ Tools & Technologies

* Power BI
* Power Query
* DAX
* Excel


