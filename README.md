# TechStream Analytics: Customer Churn & Revenue Analysis
 
**March 2026**  
**Score: 114/120
*(Grader comment: "One of the most polished and well-organized submissions in the class")*

## Overview

End-to-end analysis of customer churn and revenue for a simulated B2B SaaS company (1,000 customers, 18.7% churn rate, ~$3,576 avg MRR).  

**Key results**:
- Churn driven by monthly contracts (26% vs 3.9% multi-year), low feature usage, and low satisfaction
- Retained customers use product 5.8 points more (95% CI 3.0–8.5)
- Random Forest churn model: ~32% recall on churners
- Linear Regression revenue model: R² 0.898, RMSE $1,521
- 4 customer segments identified → clear risk/value trade-offs

## Project Structure

- **Part 1**: EDA + Altair visualizations (contract churn, company size trade-off, usage vs satisfaction)
- **Part 2**: Bootstrap inference on usage gap
- **Part 3**: Random Forest churn prediction (with CV & feature importance)
- **Part 4**: Linear Regression revenue prediction (coefficients in $)
- **Part 5**: K-means segmentation (4 clusters profiled)
- **Part 6**: Synthesis + prioritized business recommendations

## Live Notebook

Full interactive notebook:  
[![Open in nbviewer](https://img.shields.io/badge/View%20Notebook-nbviewer-orange)](https://nbviewer.org/github/mnavaya/TechStream-Churn-Revenue-Analysis/blob/main/TechStream_Churn_Revenue_Analysis.ipynb)


## Key Visuals

**Churn by Contract Type**  
![Churn by Contract](https://via.placeholder.com/800x400.png?text=Churn+by+Contract+Type)  
Monthly contracts churn 6× more than multi-year.

**Predicted vs Actual MRR**  
![Predicted vs Actual](https://via.placeholder.com/800x400.png?text=Predicted+vs+Actual+MRR)  
Linear Regression R² = 0.898

**Feature Importance – Churn Model**  
![Feature Importance](https://via.placeholder.com/800x400.png?text=Top+Churn+Features)  
Top drivers: tenure, satisfaction, usage score, monthly contracts.

**Customer Segments**  
![Segments Scatter](https://via.placeholder.com/800x400.png?text=Usage+vs+Satisfaction+by+Cluster)  
4 clusters: At-Risk, Loyalists, High-Value Enterprises, Growing Small.

## Recommendations

1. **Usage Accelerator** for At-Risk segment → estimated 20–40% churn reduction  
2. **Monthly → Annual conversion incentives** → 5–10% overall churn drop  
3. **Premium support for High-Value Enterprises** → +5–10% MRR growth  
4. **Nurture Growing Small** → sustain low churn & enable upsell

## Tools & Stack

- Python · Pandas · Scikit-learn · Altair · Random Forest · Linear Regression · K-means  
- All visualizations created with Altair (consistent professional styling)

## Learnings & Reflection

- Prioritizing recall over accuracy in churn models is critical for business impact  
- Segment naming must be validated against actual profiling data  
- Linear regression coefficients provide direct $ impact interpretation — powerful for executives

Feel free to explore the full notebook above. Questions or feedback welcome!
