# Data Analytics & Business Intelligence Portfolio

Welcome to my GitHub portfolio!

This repository contains real-world data analytics projects where I apply **SQL, Python, Excel, and Power BI** to transform raw data into actionable business insights. Each project demonstrates end-to-end analytical workflows including data cleaning, exploratory data analysis (EDA), visualization, and business-driven recommendations.

---


## Technical Skills

* **Languages:** SQL, Python
* **Libraries:** Pandas, Matplotlib
* **Visualization:** Power BI, Excel
* **Databases:** PostgreSQL
* **Other Tools:** VS Code, GitHub

---

## Projects

### Foodpanda Operations & Sales Analysis

**Objective:** Analyze customer behavior, restaurant performance, and delivery efficiency using 6,000 transactions.

**Key Highlights**

* Subway identified as top revenue-generating restaurant
* Multan highest-grossing city
* 66% of orders were delayed or cancelled
* Teenagers represent the highest-spending age group

**Tools Used:** Excel, Python (Pandas, Matplotlib)

---

### E-commerce Sales Analysis (Malaysia Market)

**Objective:** Build an end-to-end data pipeline and interactive Power BI dashboard using 10,000+ transactions from Shopee, Lazada, and TikTok Shop.

**Key Highlights**

* Total Revenue: RM 302M
* Top Product: Xiaomi Redmi Note 12
* Electronics & Fashion dominate sales
* Strong performance in Petaling Jaya, Kuala Terengganu, Kota Bharu

**Tools Used:** SQL (PostgreSQL), Power BI, Excel, VS Code

---

## Project Workflow

1. Data Collection
2. Data Cleaning & Validation
3. Exploratory Data Analysis
4. Feature Engineering
5. Visualization & Dashboarding
6. Insight Generation & Recommendations

---

## Example SQL Query

<pre class="overflow-visible! px-0!" data-start="2458" data-end="2638"><div class="contain-inline-size rounded-2xl corner-superellipse/1.1 relative bg-token-sidebar-surface-primary"><div class="sticky top-[calc(var(--sticky-padding-top)+9*var(--spacing))]"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-bg-elevated-secondary text-token-text-secondary flex items-center gap-4 rounded-sm px-2 font-sans text-xs"></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre! language-sql"><span><span>SELECT</span><span> 
    product,
    </span><span>SUM</span><span>(quantity) </span><span>AS</span><span> total_units_sold,
    </span><span>SUM</span><span>(totalamount) </span><span>AS</span><span> total_sales
</span><span>FROM</span><span> ecommerce_sales
</span><span>GROUP</span><span></span><span>BY</span><span> product
</span><span>ORDER</span><span></span><span>BY</span><span> total_sales </span><span>DESC</span><span>
LIMIT </span><span>10</span><span>;
</span></span></code></div></div></pre>

---
