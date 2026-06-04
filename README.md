# DecodeLabs Internship — Project 3 Submission

This repository contains the final submission for Project 3: SQL Data Analysis under the DecodeLabs Industrial Training Track.

The objective of this phase was to shift from general data profiling to structured query execution. Relational logic was applied to filter, group, aggregate, and transform raw transactional data into structured tables to assess organizational trends, product performance, and customer lifetime value metrics.

---

## Technical Framework and Key Operators

The query infrastructure was engineered using standard relational structures to generate consistent analytical data tables:
* Structural Selection: Standardized `SELECT` queries utilizing specific arithmetic and text expressions.
* Row-Level Constraints: Implemented precise conditional filtering using `WHERE` clauses.
* Attribute Grouping: Grouped records systematically via `GROUP BY` components.
* Relational Ordering: Enforced sequential data display using `ORDER BY` configurations.
* Aggregation Architecture: Applied standardized summary expressions including `COUNT()`, `SUM()`, and `AVG()`.

---

## Analytical Dimensions and Data Outlines

The data extraction workflow was mapped across six distinct business dimensions to generate targeted intelligence tables:

### 1. High-Level Performance Outlines
* Baseline Aggregations: Tracked transaction spaces containing 1,200 total entries distributed across 1,189 distinct customers.
* Volume Behaviors: Evaluated overall metrics indicating a mean cart baseline of 5.49 elements alongside a standard baseline value exceeding 1,000 units per transaction.

### 2. Longitudinal Trend Tracking
* Temporal Progressions: Aggregated total transaction volumes and baseline financial values categorized by distinct historical years (2023, 2024, and 2025).
* Historical Patterns: Identified a visible downward trend in year-over-year operational volume, noting that the highest level of baseline activity occurred in 2023.

### 3. Operational Logistics and Fulfillment Analysis
* State Tracking: Grouped transactions uniformly by system shipping status flags (Delivered, Processing, Cancelled, and Returned).
* Fulfillment Assessments: Determined that the combined rate of cancelled and returned items exceeds 40% of total transactions, highlighting explicit baseline logistical challenges.

### 4. Commercial Categories and Channel Analysis
* Product Revenue Tracking: Isolated total performance specifically for fulfilled (Delivered Only) rows, identifying laptop and phone categories as primary commercial drivers.
* Gateway Operations: Assessed payment channel volumes (Online, Credit Card, and Cash), showing clear revenue concentration in online processing streams.

### 5. Promotional Campaign and Coupon Performance
* Campaign Engagement: Evaluated performance markers for active promotional code inputs among delivered rows.
* Campaign Metrics: Identified the "SAVE10" code as the primary driver of coupon volume and total revenue.
* Yield Assessments: Confirmed that coupon-supported transactions consistently produced significantly higher total values than standard unprompted checkouts.

### 6. Acquisition and Customer Concentration Profiles
* Marketing Funnel Audits: Aggregated structural performance metrics categorized by customer referral channels, confirming that email campaigns yielded the highest absolute volume while Facebook referrals achieved the highest average value per delivered order.
* Customer Value Distribution: Isolated the top 10 individual profiles by historical spending metrics, validating a high level of financial concentration within a small user baseline.

---

## Operational Summary

All relational scripts successfully bypassed syntax and grouping constraints to transition unstructured records into structured data parameters. The resulting outputs establish a reliable layer of descriptive data intelligence, ensuring the project space is fully cleared to transition into programmatic reporting and pipeline automation tracks.
