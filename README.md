# Hotel Bookings & Performance Data Analytics Project (Excel BI Dashboard)

An end-to-end data analytics and business intelligence project built in **Microsoft Excel**, covering the full workflow from **raw data cleaning and preparation** to **exploratory analysis, KPI modeling, and an interactive multi-page dashboard**.

Both the **original dataset** and the **final Excel analysis workbook** are included in this repository so the entire analytical workflow can be reviewed and reproduced.

---

## Project Scope & Workflow

I worked on this project end-to-end across all stages:
1. **Data Cleaning & Preparation:** Inspected and cleaned the raw hotel bookings dataset, standardized fields and statuses, handled missing/inconsistent values, and prepared derived fields (such as booking revenue, lead time categories, and risk profiles) to support accurate KPI and chart calculations.
2. **Data Analysis & Modeling:** Built structured analytical summaries, Pivot Tables, and calculated metrics to examine revenue performance, cancellation drivers, geographical concentration, payment risk levels, lead time impact, and guest stay patterns.
3. **Interactive Dashboard Design:** Designed a cohesive multi-page dashboard in Microsoft Excel featuring a landing page, interactive slicers (`Hotel`, `Guest Type`, `Arrival Year`), KPI cards, and visual charts across three dedicated analytical views.

---

## Dashboard Pages & Visual Walkthrough

### 1. Landing Page
Overview hub providing direct navigation into the three analytical views of the dashboard.

![Landing Page](1-%20Landing%20Page.jpg)

---

### 2. Executive & Revenue Overview
Tracks overall booking volume, actual vs. lost revenue, cancellation rate, average daily rate (ADR), monthly revenue trends, revenue breakdown by hotel type, and revenue by market segment.

- **KPIs:** Total Bookings (`119.0K`), Actual Revenue (`$26.4M`), Lost Revenue (`$16.3M`), Cancellation Rate (`36%`), Avg. Daily Rate (`$102`).
- **Visuals:** Monthly Revenue (`Cancelled` vs. `Not Cancelled`), Actual vs. Lost Revenue by Hotel Type, and Actual Revenue by Market Segment.

![Executive & Revenue Overview](2-%20Executive%20&%20Revenue%20Overview.jpg)

---

### 3. Cancellation, Risk & Geography
Examines no-show behavior, average lead time prior to cancellation, high-risk bookings, top cancelling countries, payment risk impact, and lead time categories.

- **KPIs:** No-Show Rate (`1%`), Avg. Cancellation Lead Time (`147 Days`), High-Risk Bookings Rate (`88%`).
- **Visuals:** Top 10 Countries by Cancellation, Cancellation Rate by Payment Risk (`High Risk` vs. `Low Risk`), and Cancellation Rate by Lead Time Category (`Short`, `Medium`, `Long`).

![Cancellation, Risk & Geography](3-%20Cancellation,%20Risk%20&%20Geography.jpg)

---

### 4. Guest Behavior & Stay Patterns
Focuses on guest volume, average length of stay, repeat guest rate, guest type distribution, stay duration by guest type, and cancellation rates between new and repeat guests.

- **KPIs:** Total Guests (`76.1K`), Avg. Length of Stay (`3 Nights`), Repeat Guest Rate (`3%`).
- **Visuals:** Bookings by Guest Type (`Couple`, `Single`, `Family`), Average Stay Duration by Guest Type, and Cancellation Rate (`New` vs. `Repeat Guests`).

![Guest Behavior & Stay Patterns](4-%20Guest%20Behavior%20&%20Stay%20Patterns.jpg)

---

## Repository Contents

- **Original Dataset:** The raw hotel bookings dataset prior to/alongside the analysis workflow.
- **Excel Analysis & Dashboard Workbook:** The complete Excel file containing data cleaning/preparation, analytical tables, and interactive dashboard pages.
- **Dashboard Screenshots:**
  - `1- Landing Page.jpg`
  - `2- Executive & Revenue Overview.jpg`
  - `3- Cancellation, Risk & Geography.jpg`
  - `4- Guest Behavior & Stay Patterns.jpg`

---

## Tools & Skills Demonstrated

- **Microsoft Excel:** Data Cleaning, Data Preparation, Pivot Tables, Calculated Metrics/Measures, Slicers, Custom Charts, and Dashboard Layout Design.
- **Data Analytics:** Revenue & Cancellation Analysis, Risk & Lead Time Segmentation, Geographic & Cohort/Guest Behavior Insights, and Executive Reporting.
