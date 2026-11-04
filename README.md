# Project Rapido – Business Performance Dashboard

## 1. Project Overview: Understanding Ride-Hailing Operations Through Data

An interactive Tableau dashboard designed to analyse ride-hailing business performance using booking-level data. The project explores ride demand patterns, booking completion, cancellations, vehicle category performance, pickup locations and operational efficiency.

The dashboard transforms raw booking data into actionable business insights, helping identify demand trends, operational bottlenecks and opportunities to improve service reliability and customer experience.

## 2. Short Description

The Rapido Business Performance Dashboard provides a comprehensive overview of ride bookings, completed booking value, customer demand patterns, vehicle performance and cancellation behaviour. It enables stakeholders to monitor key operational KPIs, identify demand fluctuations across different time periods and locations, and investigate factors contributing to incomplete rides.

Through interactive visualisations and calculated KPIs, the project demonstrates how data analytics can support operational planning, performance monitoring and data-driven decision-making.

## 3. Tech Stack

The dashboard was developed using the following tools and technologies:

- 📊 **Tableau Desktop:** Primary platform for dashboard development, data visualisation and interactive reporting.
- 📂 **CSV Dataset:** Source data containing ride bookings, customer information, driver details and operational metrics.
- 🧮 **Tableau Calculated Fields:** Created calculated measures for booking completion, cancellation rates, average fare and other operational KPIs.
- 📈 **Interactive Visualisations:** KPI Cards, Bar Charts, Demand Analysis Charts, Comparative Charts and Filters.
- 🔍 **Data Analysis:** Explored booking trends, vehicle categories, pickup locations and incomplete ride patterns.
- 📁 **File Formats:** CSV, TWBX and dashboard screenshots.

## 4. Data Source

**Source:** Third-party Rapido-labelled Ride Booking Dataset  
**Dataset:** July 2025 Ride Booking Data

The dataset contains approximately 30,000 booking records and 25 attributes covering different aspects of ride-hailing operations.

Key attributes include:

- Booking ID and Booking Status
- Customer ID and Driver ID
- Booking Value
- Pickup and Drop Locations
- Ride Distance and Ride Duration
- Vehicle Type
- Payment Method
- Customer and Driver Ratings
- Customer and Driver Cancellations
- Incomplete Ride Reasons
- V_TAT and C_TAT

The dataset was connected to Tableau and prepared for analysis through data type validation, field selection and calculated KPI creation.

## 5. Features / Highlights

### • Business Problem

Ride-hailing platforms operate across multiple locations and vehicle categories while managing fluctuating customer demand, driver availability and ride fulfilment.

Understanding operational performance becomes challenging when booking data is spread across multiple attributes and metrics.

Key business questions include:

- How many bookings are successfully completed?
- What percentage of bookings are cancelled or incomplete?
- When does ride demand peak throughout the day?
- Which vehicle category contributes the highest booking volume?
- Which pickup locations generate the most bookings?
- Are cancellation rates significantly different across vehicle categories?
- What are the most common reasons for incomplete rides?

### • Goal of the Dashboard

The dashboard aims to:

- Monitor overall ride-hailing performance through key KPIs.
- Analyse booking completion and cancellation trends.
- Identify hourly and weekday demand patterns.
- Compare booking performance across vehicle categories.
- Evaluate pickup-location performance.
- Investigate the reasons behind incomplete rides.
- Translate operational data into actionable recommendations.

### • Walkthrough of Key Visuals

**1. KPI Overview Cards**

The dashboard provides a consolidated view of business performance through four key metrics:

| KPI | Value |
|---|---:|
| Total Bookings | 30,000 |
| Completed Rides | 24,641 |
| Completed Booking Value | ₹34,47,120 |
| Average Ride Fare | ₹139.90 |

These KPIs provide a quick overview of booking volume, ride fulfilment and completed booking value.

**2. Hourly Booking Demand**

A bar chart visualises booking distribution across 24 hours of the day.

Key Insight: Noticeable demand peaks appear around 3 AM and 4 PM in the dataset.

Business Value: Helps identify high-demand periods and supports demand-based operational planning.

**3. Weekday Demand Analysis**

A bar chart compares booking volumes across all seven days of the week.

Key Insight: Tuesday, Wednesday and Thursday show relatively higher booking volumes compared with other weekdays.

Business Value: Helps identify weekday demand variations and plan operational coverage accordingly.

**4. Peak Booking Period Analysis**

Bookings are segmented into four time categories:

- Morning
- Afternoon
- Evening
- Night

Business Value: Provides a simplified view of demand distribution across different parts of the day.

**5. Vehicle Type Analysis**

A comparative bar chart evaluates booking distribution across Bike and Auto categories.

Key Insight: Bike bookings account for a larger share of total bookings than Auto bookings.

Business Value: Helps understand vehicle-category demand and supports fleet allocation decisions.

**6. Cancellation Rate by Vehicle Type**

A comparative visualisation evaluates cancellation percentages across vehicle categories.

Key Insight: Bike and Auto cancellation rates are broadly similar, at approximately 11.9% each.

Business Value: Suggests that vehicle category alone may not explain cancellation behaviour. Further investigation into pickup locations, timing and cancellation patterns could help identify underlying issues.

**7. Pickup Location Analysis**

A horizontal bar chart ranks pickup locations according to booking volume.

Business Value: Helps identify high-demand locations and provides a basis for location-specific operational planning.

**8. Location-wise Cancellation Analysis**

A comparative chart evaluates cancellation rates across different pickup locations.

Business Value: Helps identify potential cancellation hotspots and locations that may require further operational investigation.

**9. Incomplete Ride Reasons**

A horizontal bar chart categorises the reasons associated with incomplete bookings.

Recorded reasons and booking counts:

| Incomplete Ride Reason | Bookings |
|---|---:|
| Network Issue | 380 |
| Customer Cancelled Early | 367 |
| Driver Delayed | 362 |
| Customer Not Found | 356 |
| Weather Issue | 335 |
| **Total** | **1,800** |

Key Insight: Network issues represent the most frequently recorded reason, followed by early customer cancellations and driver delays.

Business Value: Helps prioritise investigations into connectivity, driver coordination and customer communication.

## 6. Business Insights & Recommendations

### • 1. Booking Fulfilment and Cancellation Performance

Out of 30,000 total bookings:

- 24,641 rides were completed (82.14%).
- 3,559 bookings were cancelled (11.86%).
- 1,800 bookings were incomplete (6%).

**Business Insight:** Approximately 17.86% of bookings did not result in a completed ride.

**Recommendation:** Monitor cancellation and incomplete-ride rates as separate operational KPIs. Investigate the reasons behind unsuccessful bookings to identify opportunities to improve ride fulfilment.

### • 2. Demand-Based Operational Planning

The hourly demand analysis reveals noticeable booking peaks around 3 AM and 4 PM, while weekday analysis indicates stronger activity from Tuesday to Thursday.

**Business Insight:** Ride demand varies across both time of day and day of week.

**Recommendation:** Use historical demand patterns to plan driver availability and operational coverage around high-demand periods. Validate these patterns using additional months of data before making long-term staffing decisions.

### • 3. Vehicle Category Performance

Bike bookings contribute a larger share of total bookings compared with Auto bookings. However, cancellation rates remain broadly similar across the two categories.

**Business Insight:** Higher booking volume does not necessarily indicate better ride fulfilment.

**Recommendation:** Evaluate vehicle categories using multiple metrics, including booking volume, cancellation rate, completed rides and average fare, rather than relying on booking counts alone.

### • 4. Location-Based Operational Opportunities

Pickup-location analysis provides visibility into areas with higher booking volumes, while location-wise cancellation analysis helps identify potential operational hotspots.

**Business Insight:** Booking demand and cancellation behaviour can vary across pickup locations.

**Recommendation:** Prioritise high-demand locations for operational monitoring and investigate locations with relatively high cancellation rates to identify recurring service issues.

### • 5. Incomplete Ride Analysis

Network issues account for 380 incomplete bookings, making them the most frequently recorded reason in the dataset.

**Business Insight:** Incomplete rides are associated with multiple factors, including connectivity, customer cancellations, driver delays and customer availability.

**Recommendation:** Investigate network-related failures, improve customer-driver coordination and monitor driver delays to identify potential improvements in ride completion.

## 7. Business Value & Potential Impact

**Operational Efficiency**

Monitor ride completion, cancellations and incomplete bookings to identify areas requiring operational attention.

**Demand Forecasting & Planning**

Use hourly and weekday booking trends to support demand-based driver allocation and operational coverage.

**Fleet Planning**

Compare Bike and Auto demand to support vehicle-category planning and resource allocation.

**Location-Based Decision Making**

Identify high-demand pickup locations and potential cancellation hotspots for more focused operational monitoring.

**Customer Experience**

Investigate incomplete ride reasons and cancellation behaviour to identify opportunities to improve ride reliability and customer satisfaction.

**Data-Driven Decision Making**

Consolidate multiple operational metrics into an interactive dashboard, enabling stakeholders to explore performance trends and make informed decisions.

## 8. Dashboard Features

The interactive Tableau dashboard includes:

- Executive KPI Overview
- Hourly Booking Demand
- Weekday Demand Analysis
- Peak Booking Period Analysis
- Vehicle Type Comparison
- Vehicle-wise Cancellation Analysis
- Pickup Location Performance
- Location-wise Cancellation Analysis
- Incomplete Ride Reason Analysis
- Interactive Filters for Pickup Location, Vehicle Type and Date

## 9. Key Findings at a Glance

✔ 30,000 total bookings analysed, with 82.14% successfully completed.

✔ Completed rides generated a total booking value of ₹34.47 lakh, with an average fare of ₹139.90.

✔ 11.86% of bookings were cancelled, while 6% were marked incomplete.

✔ Bike bookings account for a larger share of booking volume than Auto bookings.

✔ Cancellation rates are broadly similar across Bike and Auto categories.

✔ Tuesday–Thursday demonstrate relatively higher booking activity.

✔ Network issues are the most frequently recorded reason for incomplete rides.

✔ Hourly and location-wise analysis provides opportunities for demand-based operational planning and targeted investigation.

## 10. Project Scope & Limitations

- This is an independent analytical project using a third-party Rapido-labelled dataset. It is not official Rapido company reporting.
- The dataset covers July 2025 only; therefore, long-term growth and month-on-month trends cannot be established.
- Booking Value represents completed booking value and should not be interpreted as net platform revenue.
- Driver utilisation and driver acceptance rates cannot be reliably calculated because driver availability and dispatch-level data are not provided.
- V_TAT and C_TAT are retained as dataset metrics without assigning operational definitions that have not been independently verified.
- Recommendations represent potential operational opportunities, not measured business improvements.

## 11. Project Outcome

Built an interactive Tableau dashboard that transforms 30,000 ride-booking records into a structured view of business and operational performance.

The project demonstrates practical application of KPI development, calculated fields, data visualisation, operational analysis and insight-driven recommendations to a real-world mobility business scenario.
