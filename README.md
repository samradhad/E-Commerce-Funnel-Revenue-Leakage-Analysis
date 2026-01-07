# E-Commerce Funnel & Revenue Leakage Analysis

## Overview
This project analyzes an end-to-end e-commerce user funnel to identify conversion drop-offs and revenue leakage across key stages of the purchase journey. Using SQL-based data transformations and an interactive Power BI dashboard, the analysis surfaces behavioral and segment-level drivers impacting overall conversion performance.

## Problem Statement
E-commerce platforms often experience significant user drop-offs between funnel stages, leading to hidden revenue leakage. This project aims to:
- Quantify stage-wise conversion losses
- Identify high-impact leakage points
- Surface actionable insights across product, device and discount segments

## Data & Methodology
- Built a **user-level funnel** using SQL transformations on transactional and session-level data
- Modeled funnel stages including browsing, cart, checkout and payment
- Computed key KPIs such as:
  - End-to-end conversion rate
  - Stage-wise drop-off percentages
  - Payment-stage revenue leakage

## Key Insights
- Observed an **end-to-end conversion rate of 0.5%**, indicating significant mid-funnel attrition
- Payment stage emerged as the largest contributor to revenue leakage
- Higher leakage observed among:
  - Consumer Electronics category
  - Desktop users
  - Non-discounted orders

## Dashboard
An interactive Power BI dashboard was developed to:
- Visualize funnel performance across stages
- Compare conversion trends by product category and device type
- Enable drill-down analysis for leakage identification

Screenshots of key dashboard views are available in the `/screenshots` directory.

## Tools & Technologies
- SQL (Funnel modeling, KPI computation)
- Power BI (Dashboarding & visualization)
- Data modeling & analytical reporting
