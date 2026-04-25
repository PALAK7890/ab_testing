# Marketing Analytics: A/B Testing, Profitability and Budget Optimization

## Overview

This project presents a structured, end-to-end marketing analytics workflow that connects experimental analysis with financial performance and strategic decision-making. It evaluates whether advertising improves user behavior, assesses whether that improvement translates into profitability, and determines how to allocate budget under constrained conditions.

The analysis moves beyond descriptive metrics to answer a core business question:

What is the true impact of advertising on conversions and profitability, and how should limited budget be allocated to improve efficiency?

---

## Key Results

* Ad campaign conversion rate: ~2.55%
* Control group conversion rate: ~1.79%
* Relative conversion lift: ~43%
* Statistical significance: p < 0.001
* Effect size: small but reliable
* ROI across all ad formats: negative
* Optimal budget allocation: prioritize static ads, reduce carousel exposure

---

## Problem Context

Marketing teams often optimize campaigns based on engagement or conversion metrics without evaluating financial outcomes. This creates a disconnect between performance indicators and business value.

This project addresses three fundamental questions:

* Do ads significantly improve conversion rates?
* Are those improvements financially sustainable?
* How should budget be allocated when all channels underperform?

---

## Methodology

### 1. Data Preparation

* Cleaned and standardized user-level dataset
* Engineered features such as exposure buckets and time segments
* Structured data for both statistical analysis and visualization

### 2. A/B Testing and Statistical Validation

* Two-proportion z-test to compare conversion rates
* Confidence interval estimation for uplift
* Effect size (Cohen’s h) to measure practical impact

### 3. Profitability Analysis

* Simulated revenue and cost structure per ad type
* Computed:

  * Total cost
  * Revenue
  * Profit
  * Return on investment (ROI)

### 4. Budget Optimization

* Developed ROI-weighted allocation model
* Compared equal vs optimized allocation
* Designed strategy to minimize losses under fixed budget constraint

---

## Dashboard Summary

### Dashboard 1: A/B Testing Analysis

Focus:

* Ad vs control group performance

Metrics:

* Conversion rate
* Absolute and relative lift
* Statistical significance

Insight:
Advertising significantly improves conversion rates, but the magnitude of improvement is modest in practical terms.

---

### Dashboard 2: Profitability and ROI Analysis

Focus:

* Financial performance by ad type

Metrics:

* Cost
* Revenue
* Profit
* ROI

Insight:
All ad formats generate negative ROI, indicating that increased conversions are insufficient to offset acquisition costs.

---

### Dashboard 3: Budget Optimization Strategy

Focus:

* Allocation of a fixed ₹50,000 budget

Approach:

* ROI-based weighting
* Comparison of equal vs optimized distribution

Insight:
Budget allocation should prioritize minimizing losses. Static ads receive the highest allocation due to relatively better performance, while carousel ads are significantly reduced.

---

## Business Insights

* Conversion improvements do not guarantee profitability
* Cost structure and revenue per conversion are critical drivers of ROI
* Negative ROI across channels signals inefficiency in unit economics
* Budget decisions should be based on relative performance, not intuition
* Scaling campaigns without improving ROI leads to financial loss

---

## Technical Stack

* Python (Pandas, NumPy) for data processing
* Statistical methods for experiment validation
* Tableau for interactive dashboards
* Level of Detail (LOD) expressions for stable calculations
* CSV datasets for structured analysis

---

## How to Use

1. Open the `.twbx` file in Tableau
2. Navigate across dashboards:

   * A/B Testing
   * ROI Analysis
   * Budget Optimization
3. Review insights and recommended strategy

---

## Limitations

* Revenue is simulated due to lack of real financial data
* No customer lifetime value (LTV) included
* No segmentation by user cohorts or geography
* Static assumptions for cost across ad types

---

## Future Enhancements

* Incorporate customer lifetime value into ROI analysis
* Add segmentation by audience and behavior
* Develop predictive models for conversion and revenue
* Introduce dynamic budget allocation based on real-time performance

---

## Summary

This project demonstrates how to move from experimental analysis to business decision-making. It highlights the importance of evaluating both statistical significance and financial impact, and provides a practical framework for optimizing marketing spend under real-world constraints.

The result is a cohesive analytical workflow that aligns data insights with actionable strategy.
