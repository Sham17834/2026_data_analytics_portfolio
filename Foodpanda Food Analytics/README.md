# Foodpanda Operations & Sales Analysis

## Project Overview

This project focuses on analyzing customer behavior, sales performance, and operational efficiency for  **Foodpanda** . Using a dataset of 6,000 transactions, I performed data cleaning, exploratory data analysis (EDA), and visualization to identify key trends in restaurant performance, delivery logistics, and user retention across major cities in Pakistan.

## Key Insights

* **Top Performer:** **Subway** leads in total revenue ($1,009,983), followed closely by KFC.
* **Regional Demand:** **Multan** emerged as the highest-grossing city ($1,009,003), surpassing Islamabad and Karachi.
* **Operational Bottleneck:** Approximately **66% of orders** were either Delayed or Cancelled, indicating a significant need for logistics optimization.
* **Demographics:** **Teenagers** represent the highest spending age group ($1.65M total), suggesting a strong market for fast-food oriented marketing.

---

## Analysis Workflow

### 1. Data Cleaning & Preparation

* Handled missing values and standardized date formats.
* Calculated **Average Order Value (AOV)** to better understand customer spending.
* Categorized customers into "Active" and "Inactive" based on churn data.

### 2. Sales & Market Trends

* Analyzed revenue distribution across 5 major restaurants.
* Evaluated payment method preferences; **Cash** remains the most popular (2,039 orders), followed by Card and Wallet.

### 3. Operational Performance

* Identified that **Delayed** orders (1,972) and **Cancelled** orders (1,968) are nearly equal to successful deliveries (2,060).
* Correlated delivery status with customer ratings: Cancelled orders averaged a  **2.97 rating** , impacting brand loyalty.

### 4. User Behavior

* Mapped loyalty points against churn status. Interestingly, "Inactive" users held slightly higher average loyalty points (252) than "Active" users (248), suggesting that points alone aren't preventing churn.

---

## Recommendations

1. **Improve Logistics:** Investigate the high rate of cancellations and delays in high-volume cities like Multan.
2. **Targeted Marketing:** Develop loyalty campaigns specifically for the "Adult" and "Senior" segments, as they currently trail Teenagers in total spend.
3. **Payment Incentives:** Offer discounts for "Wallet" and "Card" payments to reduce the operational overhead of Cash-on-Delivery.

## Tech Stack

* **Tools:** Excel / Python (Pandas, Matplotlib)
* **Techniques:** Data Aggregation, Pivot Tables, Trend Analysis, Descriptive Statistics
