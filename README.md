# Insurance-Portfolio-Risk-&-Pricing-Analytics-Dashboard

# 📌 Project Overview

This project explores a synthetic insurance dataset to uncover hidden patterns across risk, pricing, profitability, customer behaviour, and conversion efficiency. Using Power BI, I developed a full analytical dashboard with dedicated pages for underwriting, pricing, customer retention, and marketing funnel performance.

The goal was to:

1. Understand portfolio composition
2. Identify pricing adequacy issues
3. Analyse risk segmentation
4. Evaluate customer loyalty behaviour
5. Visualize the full customer acquisition journey
6. Provide actionable actuarial recommendations

# 🧩 Dataset Summary

The dataset contains detailed insurance customer attributes including:

1. Demographics (Age, Region, Income Band, Senior Status)
2. Risk Indicators (Claims Frequency, Claims Severity, Credit Score)
3. Pricing Fields (Premium Amount, Discounts, Prior Insurance)
4. Behavioural Metrics (Web Visits, Inquiries, Quotes Requested)
5. Conversion Status & Time to Conversion
6. Derived analytical features (Risk Tier, Loyalty Band, Engagement Level)

After cleaning and enrichment, the dataset was transformed into a fully analytics-ready model used for Power BI reporting.

# 🛠️ Tools & Technologies

Power BI – Visualization, DAX measures, dashboard design
Python (Pandas) – Data cleaning, feature engineering
Excel – Validation, preprocessing
DAX – Custom measures & calculated columns

# 📈 Dashboard Pages & Key Insights

# 1. Home / Portfolio Overview

10K policyholders analyzed
1. Conversion rate: 57.7%.
2. Average premium: £2.2K.
3. High-level view of premiums by region, policy type, and risk tier.

# 2. Underwriting & Risk Analytics

Assessed how risk metrics influence pricing and segmentation:
1. High Risk customers represent 11% of the portfolio.
2. Claims Frequency & Severity heatmaps.
3. Credit Score distribution across risk groups.
4. Identified potential misalignment between risk exposure and premium charged.

# 3. Pricing & Profitability

Compared pricing levels across risk segments:
1. Premium levels for High, Medium, and Low Risk customers showed minimal differentiation.
2. Discounts increase noticeably in lower credit score bands.
3. Premium/Discount ratio demonstrated potential cross-subsidisation.
4. Insights indicated opportunity for more risk-sensitive pricing.

# 4. Customer Loyalty & Retention

Analysed customer tenure and retention behaviour:
1. 26% of customers have been loyal for over 5 years.
2. Premium levels consistent across loyalty bands.
3. Highest discounts given to long-tenured customers.
4. Loyalty appears strongest among Low Risk customers.

# 5. Marketing & Engagement

1. Mapped the customer acquisition funnel:
Funnel: Website Visits → Inquiries → Quotes → Conversion
2. Engagement Level strongly correlated with higher premium amounts.
3. Cumulative conversion curve exposed drop-off points in customer journey.

# 6. Executive Summary & Actuarial Recommendation

Problem Identified:
Despite representing only 11% of the portfolio, High Risk policyholders pay almost the same premium as Low Risk customers. This suggests risk is not adequately reflected in pricing, which may result in:

1. Underpricing of high-risk segments.
2. Overcharging low-risk segments.
3. Potential profitability erosion.

# Recommended Solution (Actuarial Approach):

1. Build claims frequency and claims severity models.
2. Quantify expected losses by risk segment.
3. Perform loss ratio analysis to assess pricing adequacy.
4. Apply risk-adjusted premium corrections.
5. Strengthen pricing fairness while improving portfolio profitability.
