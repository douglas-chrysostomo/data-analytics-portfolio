# Nexus Media - Client Performance Dashboard

## 🎯 Business Context & Problem
A US-based digital marketing agency (Nexus Media) needed an executive, interactive dashboard to track cross-platform ad performance. The client required strict US regional data formatting (commas for thousands, periods for decimals, and proper currency signs) to present to stakeholders, which natively conflicted with Latin American account setups.

## 🛠️ Technical Solution & Implementation
* **Data Wrangling (Data Sheets):** Cleaned, structured, and validated historical marketing metrics (Spend, Revenue, ROAS) split by date and acquisition platform using Google Sheets.
* **Localization Engineering:** Overcame Google account regional locking by troubleshooting global account locale overrides, forcing strict US formatting (`$18,000.00` and `4.54x`) across all KPIs.
* **Data Visualization & Storytelling (Looker Studio):** 
  * Applied visual data storytelling principles (color contrast focus to highlight high-performing channels like Meta Ads while keeping Google Ads in a neutral layout).
  * Built dynamic `Time Series Charts` with `Year Month` granularity to track month-over-month growth patterns without daily data distortion.
  * Implemented an interactive `Date Range Control` filter alongside `Cross-filtering` capabilities for dynamic data exploration.

## 📊 Project Deliverable
* **Interactive Dashboard:** [Click here to view the live Looker Studio report](https://datastudio.google.com/reporting/7138c463-70c7-4b54-b884-eb4b1b30a6d5).
