# AirAsia Booking & Ancillary Sales Analysis

## Project Overview

This project analyzes 50,000 flight booking records from AirAsia to understand customer behavior regarding **ancillary services** (Baggage, Meals, Seat Selection) and **Travel Insurance**. By identifying which factors lead to higher conversion rates, this analysis provides data-driven recommendations to optimize revenue per passenger. Key Business Questions Explored

* **Channel Efficiency:** Which sales channel (Internet vs. Mobile) yields the highest insurance conversion?
* **Ancillary Correlation:** Does purchasing baggage increase the likelihood of buying travel insurance?
* **Route Dynamics:** How does flight duration impact the "AnyAncillary" purchase rate?
* **Time of Day:** Does the booking hour influence the type of services a customer selects?

## Data Stack

* **Excel/Tableau:** Used for data cleaning, Pivot Table analysis, and dashboard visualization.
* **Data Size:** 50,000 unique booking entries.
* **Key Metrics:** Insurance Conversion Rate (ICR), Meal Upsell Rate, Ancillary Propensity.

## Key Insights (Sample Findings)

Based on the `Pivot_table.csv` and `Raw_Data.csv`:

* **Booking Channel Performance:** * **Internet:** 44,382 bookings with a **15.48%** insurance conversion rate.
  * **Mobile:** 5,618 bookings with a **10.84%** insurance conversion rate.
  * *Insight:* Desktop users are significantly more likely to complete insurance purchases than mobile users.
* **Baggage & Insurance Link:** * Passengers who purchased baggage have a higher propensity to buy insurance ( **16.67%** ) compared to those who didn't ( **11.50%** ).
* **Flight Duration:**
  * There is a visible trend where specific flight durations (e.g., 5-hour flights) see higher insurance uptake ( **25.7%** ) compared to 6-hour flights ( **12.5%** ).

## File Description

* **`AirAsia Booking Raw Data.csv`** : The primary dataset containing PAX count, sales channels, lead times, and flight details.
* **`Pivot_table.csv`** : Aggregated data used to calculate conversion rates and ancillary performance.
* **`Airasia Dashboard.png`** : A high-level visual representation of the findings (Total Bookings, Revenue Breakdown, and Regional Trends).

## Recommendations for AirAsia

1. **Mobile UI/UX Optimization:** Investigate why mobile users convert at a 5% lower rate for insurance. Simplify the "Add-on" screen in the AirAsia SuperApp.
2. **Strategic Bundling:** Create a "Traveler’s Essential" bundle (Baggage + Insurance) specifically for routes with flight durations over 5 hours.
3. **Lead Time Targeting:** Customers with long `PURCHASELEAD` times are more likely to plan; target them with early-bird meal deals via email marketing.
