# Task 1 – Data Analysis Workflow

This document describes the end-to-end analytical workflow for the Brent Oil
Change Point Analysis project.

---

## 1. Data Ingestion
- Load daily Brent crude oil prices from CSV
- Standardize date formats
- Sort data chronologically
- Validate missing or invalid entries

---

## 2. Exploratory Data Analysis (EDA)
- Visualize long-term price trends
- Compute descriptive statistics
- Calculate log returns
- Analyze volatility patterns

---

## 3. Time Series Diagnostics
- Test stationarity using Augmented Dickey-Fuller (ADF)
- Compare price levels vs. log returns
- Identify trend changes and volatility clustering

---

## 4. Event Data Integration
- Compile major geopolitical, economic, and OPEC-related events
- Structure events in a tabular dataset
- Align events with price movements for interpretation

---

## 5. Change Point Modeling (Planned)
- Apply Bayesian change point detection models
- Identify structural breaks in mean and volatility
- Estimate regime-specific parameters

---

## 6. Insight Generation
- Interpret detected change points
- Relate changes to historical events
- Document assumptions and limitations

---

## 7. Communication & Delivery
- Technical notebooks for analysts
- PDF reports for stakeholders
- Analytical API and dashboards (Task 3)
