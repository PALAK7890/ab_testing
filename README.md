# Marketing Analytics: A/B Testing, Profitability and Budget Optimization

## Overview

This project presents a structured analytics workflow covering three critical stages of marketing decision-making:

1. Experiment evaluation (A/B testing)
2. Financial performance analysis (ROI and profitability)
3. Budget optimization under constrained spend

The objective is to move beyond surface-level metrics and answer a core business question:

What is the true impact of advertising on both conversions and profitability, and how should budget be allocated to improve efficiency?

---

## Problem Statement

Marketing teams often optimize for conversion rates without fully understanding financial outcomes. This creates a gap between performance metrics and actual business value.

This project addresses:

* Whether ads drive statistically significant improvement in conversions
* Whether that improvement translates into profitability
* How to allocate limited budget when all channels are underperforming

---

## Data and Methodology

### Data

* User-level A/B testing dataset (ad vs control group)
* Aggregated performance metrics by ad type

### Approach

* Data cleaning and feature engineering in Python
* Statistical testing using two-proportion z-test
* ROI and profitability computation
* Optimization logic based on relative performance

---

## Dashboard Summary

#LINK =https://public.tableau.com/app/profile/palak.5572/viz/ab_testing_marketing_optimization_twbx/Story1?publish=yes

### Dashboard 1: A/B Testing Analysis

Focus:

* Ad vs control group comparison

Metrics:

* Conversion rate
* Absolute and relative lift
* Statistical significance

Method:

* Two-proportion z-test
* Confidence interval estimation
* Effect size calculation

Key Finding:
Advertising increases conversion rates with statistical significance, but the magnitude of improvement is modest.

---

### Dashboard 2: Profitability and ROI Analysis

Focus:

* Financial performance across ad types

Metrics:

* Total cost
* Total revenue
* Profit
* Return on investment

Comparison:

* Static
* Video
* Carousel

Key Finding:
All ad formats generate negative ROI. Increased conversions do not offset acquisition costs, indicating weak unit economics.

---

### Dashboard 3: Budget Optimization Strategy

Focus:

* Allocation of a fixed budget (₹50,000)

Method:

* ROI-based weighting
* Comparison of equal vs optimized allocation

Outputs:

* Recommended budget by ad type
* Allocation percentage
* Efficiency comparison

Key Finding:
Budget should be allocated to minimize losses rather than maximize returns. Static ads receive the highest allocation due to relatively better performance, while carousel ads are deprioritized.

---

## Key Insights

* Conversion rate alone is not a sufficient performance metric
* Profitability must be evaluated alongside growth metrics
* Negative ROI across channels indicates structural inefficiency
* Budget optimization should be guided by relative performance
* Scaling campaigns without improving unit economics leads to value destruction

---

## Technical Implementation

* Python (Pandas, NumPy) for data preparation
* Statistical testing for experiment validation
* Tableau for dashboard development and visualization
* Level of Detail (LOD) expressions for stable calculations
* Aggregation and transformation for business metrics

---

## Business Implications

* Marketing effectiveness should be evaluated end-to-end, not in isolation
* Budget decisions must incorporate cost efficiency, not just engagement
* Optimization frameworks should prioritize loss minimization when ROI is negative
* Strategic improvements should focus on reducing acquisition cost and increasing revenue per conversion

---

## Limitations

* Dataset does not include long-term customer value (LTV)
* No segmentation by audience or geography
* Static cost assumptions across ad types
* No temporal modeling of campaign performance

---

## Future Enhancements

* Incorporate customer lifetime value into ROI calculations
* Segment performance by user cohorts
* Introduce predictive modeling for budget allocation
* Build dynamic optimization based on real-time performance

---

## Summary

This project demonstrates the transition from descriptive analytics to decision-oriented analysis. It highlights the importance of connecting experimentation, financial evaluation, and strategic planning into a single coherent framework.

The outcome is a practical approach to marketing optimization grounded in data and aligned with business objectives.
