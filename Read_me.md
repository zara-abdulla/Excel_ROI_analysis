# 📊 Social Media Campaign ROI Analysis (Excel Project)

## 📌 Project Overview

This project analyzes the **Return on Investment (ROI)** of social media marketing campaigns using **Excel Pivot Tables, Pivot Charts, and Dashboards**.

The objective was to evaluate how campaigns across **Instagram, TikTok, Twitter, and YouTube** performed in terms of **product sales, estimated reach, and engagements**.

An interactive dashboard was designed with KPIs, slicers, and seven visualizations to provide a clear picture of campaign effectiveness.

## 📂 Dataset

The dataset included:

- **Campaign ID**
- **Platform** (Instagram, TikTok, Twitter, YouTube)
- **Influencer Category** (Beauty, Fashion, Food, Gaming, etc.)
- **Campaign Type** (Product Launch, Seasonal Sale, Event Promotion, etc.)
- **Start Date / End Date**
- **Campaign Duration (days)**
- **Engagements**
- **Estimated Reach**
- **Product Sales** (quantity of products sold)

Additional calculated KPIs:

- **Sales per Reach**
- **Sales per Engagement**

## 🧹 Data Cleaning

Before analysis, we cleaned and standardized the dataset:

- Removed **duplicate Campaign IDs**.
- Reformatted Campaign IDs (removed the word *“Camp”*, leaving only numeric IDs).
- Standardized column formats (dates → date format, numbers → numeric, text → text).
- Filled missing values in dates/duration by recalculating based on available fields.
- Cleaned **Product Sales** column (removed symbols like $, € since it represents quantity, not cost).

## 📊 Dashboard Design & Analysis

The dashboard included **six charts and one pivot table**, with interactive slicers.

### 🔎 Slicers

- **Years (timeline)**
- **Influencer Category**
- **Platforms**

### 📈 Visualizations

1. **Pie Chart** – Count of campaigns per platform  
2. **Column Chart** – Sales, reach, and engagement by platform  
3. **Bar Chart** – Platform vs. campaign sales  
4. **Table** – Sales efficiency by category  
5. **Column Chart** – Engagement rate by campaign days (1–7, 8–14, 15–21, 22–29 days)  
6. **Line Chart** – Monthly performance 
7. **Column Chart** – Engagement per category  

### KPIs

- **Total Product Sales**  
- **Count of Campaigns**  
- **Average Engagements**  
- **Sales per Reach**  
- **Sales per Engagement**

## 🔍 Key Insights

- **Overall KPIs**  
    - **Total Product Sales:** 3.29M units  
    - **Count of Campaigns:** 1,336  
    - **Average Engagements per Campaign:** ~49K  
    - **Sales per Engagement:** ~4.97%  
    - **Sales per Reach:** ~0.49%

- **Platform Performance**  
    - **Instagram** generated the highest sales (~1.3M)  
    - **YouTube:** ~974K sales  
    - **TikTok:** strong engagement but lower sales conversion  
    - **Twitter:** least contribution in sales & engagement

- **Engagement per Category**  
    - **Food:** highest average engagement (~51K)  
    - **Gaming, Beauty, Travel, Tech:** mid-range (~49K)  
    - **Fitness:** lowest engagement (~47K)

- **Sales Efficiency by Category**  
    - Highest **Sales per Reach:** Travel (0.52%), Food (0.51%)  
    - Highest **Sales per Engagement:** Tech (5.18%), Fitness (5.14%), Fashion (5.10%)  
    - Beauty & Food: large audience, lower conversion  
    - Fitness: smaller audience, more loyal buyers  
    - Tech & Fashion: balanced engagement & sales  
    - Travel: strong in both reach & sales conversion

- **Campaign Duration**  
    - **22–29 days**: best performance (~19M engagements, ~961K sales)  
    - **1–7 days**: lower performance (~7.8M engagements)

- **Monthly Trends**  
    - Sales peaked in **July–August** (~320K)  
    - After August: sales decline, stabilize ~225K  
    - Strong **seasonal effect**, summer campaigns best
