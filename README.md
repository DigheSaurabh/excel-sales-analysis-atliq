# AtliQ Hardwares Excel Analytics Project

A recruiter-friendly Excel analytics project simulating real-world business reporting for AtliQ Hardwares. It analyzes multi-year sales across channels, customers, products, and regions using Power Query, Pivot Tables, VBA, data modeling, and EDA.

---

## Table of Contents
- Overview
- Objectives
- What I Built
- Key Insights
- Deliverables
- How to Use
- Project Structure
- Tech & Skills
- What This Demonstrates
- Contact

---

## Overview
AtliQ Hardwares is a fictional manufacturer selling monitors, laptops, mice, and related products. Its customers are retailers and platforms—brick-and-mortar (Best Buy, Croma, Staples) and e-commerce (Amazon, Flipkart)—who sell to end consumers. Distribution operates through three channels: retailer, direct, and distributor. This project replicates a corporate analytics environment to evaluate multi-channel sales performance, customer segmentation, product success, and regional profitability.

---

## Objectives
- Build an Excel-based analytics solution replicating enterprise reporting.
- Clean, model, and analyze multi-year sales across channels, customers, products, and regions.
- Deliver interactive dashboards and automated reporting for decision support.

---

## What I Built
- Power Query ETL:
  - Combined multiple files/tables, standardized formats, fixed types, removed duplicates.
  - Reusable transformation steps for refreshable pipelines.
- Data Modeling:
  - Star-like model: Fact Sales linked to Date, Customer, Product, Market/Channel.
  - Calculated columns and measures: Net Sales, Quantity Sold, Gross Margin, GM%, YoY growth.
- EDA & Reporting:
  - Trends by year/quarter/month.
  - Channel analysis (retailer, direct, distributor).
  - Customer segmentation (brick-and-mortar vs e-commerce).
  - Product/category performance and new launches.
  - Country/sub-zone performance and margin variance.
- Advanced Excel:
  - Pivot Tables/Charts with slicers and timelines.
  - XLOOKUP/VLOOKUP/INDEX-MATCH for enrichment and reconciliation.
  - VBA macros to refresh queries, update pivots, and export reports.
- Storytelling:
  - Interactive dashboards with KPIs, top customers/products, regional heatmaps.
  - Clear business definitions and assumptions.

---

## Key Insights
- Multi-year sales growth driven by strong performance in e-commerce and leading retailers.
- Clear separation of customers (stores/platforms) vs consumers sharpened B2B insights.
- Product analysis highlighted breakout SKUs and successful new launches in 2021.
- Regional analysis surfaced high-GM markets and pricing/cost optimization opportunities.
- Channels play complementary roles: retailer for scale, distributor for reach, direct for key accounts.

---

## Deliverables
- Excel workbook(s):
  - Power Query transformations
  - Data model with relationships and measures
  - Pivot-driven dashboards with slicers/timelines
  - VBA automation (where applicable)
- Documentation (PDF/Markdown):
  - Business context, data dictionary, KPI definitions, methodology
  - Executive summary with insights and recommended actions
- Visuals:
  - Dashboard screenshots and charts

---

## How to Use
1. Prerequisites:
   - Microsoft Excel 2016+ (Excel 365 recommended)
   - Enable macros (VBA) for automation features
2. Open:
   - Main workbook in /data or root (see structure below)
3. Refresh & Interact:
   - Data > Refresh All to run Power Query
   - Use slicers/timelines to filter by year, channel, customer type, product, region
   - Run macros via Developer tab or dashboard buttons (if provided)
4. Review:
   - Insights/Executive Summary sheet or /docs summary for key takeaways

---

## Project Structure
