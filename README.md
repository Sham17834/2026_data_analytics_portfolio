# Data Analytics Portfolio – Business Insights & Revenue Optimization

Welcome to my data analytics portfolio. This repository showcases end-to-end analytical projects focused on **customer behavior, revenue optimization, and business decision-making**, using real-world datasets from the **aviation** and **e-commerce** industries.

Each project demonstrates my ability to:
- Clean and validate raw data
- Apply business logic and metrics
- Perform exploratory and diagnostic analysis
- Translate insights into **actionable business recommendations**
- Communicate findings through dashboards and structured analysis

---

## Projects Overview

### AirAsia Booking & Ancillary Sales Analysis

**Objective:**  
Analyze 50,000 flight booking records to understand customer behavior toward **ancillary services** (Baggage, Meals, Seat Selection) and **Travel Insurance**, with the goal of increasing **revenue per passenger**.

**Key Business Questions:**
- Which booking channel (Internet vs Mobile) converts better for insurance?
- Does purchasing baggage increase the likelihood of insurance uptake?
- How does flight duration impact ancillary purchase behavior?
- Does booking time influence service selection?

**Dataset:**
- 50,000 unique AirAsia booking records

**Tools & Stack:**
- Excel (Data Cleaning & Pivot Tables)
- Tableau (Dashboard Visualization)

**Key Metrics:**
- Insurance Conversion Rate (ICR)
- Ancillary Purchase Rate
- Meal Upsell Rate

**Key Insights:**
- **Internet bookings** show a higher insurance conversion rate (15.48%) compared to **Mobile** (10.84%).
- Passengers who purchase **baggage** are significantly more likely to buy **travel insurance**.
- Certain **longer flight durations** (>5 hours) show stronger insurance uptake.
- Booking time influences the type of ancillaries selected.

**Business Recommendations:**
- Optimize Mobile UI/UX for ancillary add-ons.
- Bundle **Baggage + Insurance** for long-haul routes.
- Target long lead-time customers with early-bird meal promotions.

**Files:**
- `AirAsia Booking Raw Data.csv`
- `Pivot_table.csv`
- `Airasia Dashboard.png`

---

### E-commerce Sales Analysis & Insights (Malaysia Market – 2024)

**Objective:**  
Transform raw transactional data into actionable insights to understand **sales performance, customer behavior, and platform dynamics** in the Malaysian e-commerce market.

**Dataset:**
- 10,000+ e-commerce transactions (Malaysia, 2024)

**Tools & Stack:**
- SQL (PostgreSQL) – Data Cleaning & EDA
- Power BI – Interactive Dashboard (DAX)
- Excel, VS Code

**Data Processing & Cleaning:**
- Removed duplicate Order IDs
- Handled missing values and whitespace inconsistencies
- Filtered invalid transactions (negative price/quantity)
- Recalculated revenue fields for consistency
- Restricted analysis to FY2024
