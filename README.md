# 🛒 Istanbul Retail Data Analysis (2021–2023)

Welcome to the world of retail insights in Istanbul! This project explores transactional data from 10 major shopping malls across the city, covering 99,000+ purchases between 2021 and 2023. Through exploratory data analysis, regression modeling, and customer segmentation, we uncover patterns in shopper behavior, category performance, and mall-level sales dynamics.

---

## 📌 Project Objective

This project aims to analyze real-world consumer shopping data to:

- Understand demographic and behavioral patterns of shoppers
- Identify best-selling product categories by age and gender
- Evaluate shopping mall performance over time
- Cluster customers into meaningful groups for targeted strategies
- Explore total sales and average purchase value across categories

---

## 📊 Dataset Overview

| Feature          | Description                             |
|------------------|-----------------------------------------|
| `invoice_no`     | Unique transaction ID                   |
| `customer_id`    | Unique customer identifier              |
| `gender`         | Gender of the shopper                   |
| `age`            | Customer's age                          |
| `category`       | Product category purchased              |
| `quantity`       | Quantity of items bought                |
| `price`          | Total price of the transaction          |
| `payment_method` | Payment type (Cash, Credit, Debit)      |
| `invoice_date`   | Date of purchase                        |
| `shopping_mall`  | Mall where transaction occurred         |

- **Total Records**: 99,457
- **Date Range**: January 2021 – February 2023
- **Unique Malls**: 10 (e.g., Mall of Istanbul, Kanyon, Metrocity)

---

## 📈 Exploratory Data Analysis

### 🎂 Age Distribution
- Shoppers aged **30–56** dominate purchases
- Mean age: **43.4 years**

### 🧍 Who Shops More?
- **Females**: 59.8% of purchases
- **Males**: 40.2%

### 🧢 Preferred Categories by Gender
| Category     | Female (%) | Male (%) |
|--------------|------------|----------|
| Clothing     | High       | Moderate |
| Cosmetics    | High       | Low      |
| Technology   | Low        | High     |

### 💸 Category-Wise Financial Insights
| Category     | Quantity | Revenue (₺)      |
|--------------|----------|------------------|
| Clothing     | 103,558  | ₺3.2 Trillion     |
| Shoes        | 30,217   | ₺547.9 Billion    |
| Technology   | 15,021   | ₺236.9 Billion    |
| Cosmetics    | 45,465   | ₺84.0 Billion     |
| Toys         | 30,321   | ₺32.9 Billion     |

### 🏬 Mall Performance by Year
- Top-performing malls: **Mall of Istanbul**, **Kanyon**, **Metrocity**
- Trend analysis using regression smoothing

---

## 📊 Modeling & Insights

### 📉 Smooth Layer Regression
- Yearly regression lines show seasonal demand spikes and mall performance trends

### 🔍 Clustering
- **K-Means clustering** segments customers into:
  - Bargain Buyers (low spend, high quantity)
  - Trend Seekers (young, high volume in fashion)
  - Premium Shoppers (older, tech-focused)

---

## 🧠 Key Takeaways

- **Clothing** dominates both volume and revenue
- **Females** drive more sales in fashion and cosmetics
- **Technology** and **Shoes** generate higher individual transaction values
- **Younger shoppers** lean toward fashion; **older shoppers** prefer books and souvenirs
- - **Credit Cards** and **Cash** are most used
- Mall performance varies across time — some see consistent seasonal spikes


---

## 🛠️ Tech Stack

- **Language**: R
- **Libraries**: `tidyverse`, `lubridate`, `ggplot2`, `dplyr`, `cluster`, `summarytools`
- **Tools**: RStudio, GitHub, Excel for validation


---

## 📈 Future Work

- Association Rule Mining (Apriori, FP-Growth)
- Time-Series Sales Forecasting
- Customer Lifetime Value (CLV) Modeling

---

## 🤝 Connect

📢 *“Retail is detail.” Let’s decode it with data!*  
Feel free to connect and discuss the project.
