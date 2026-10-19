# Week 3: Comprehensive Marketing Analysis & Strategy Report

## Overview
This document summarizes the complete workflow and deliverables completed during **Week 3** of our data-driven marketing analysis. The project bridges exploratory data analysis (EDA), statistical validation, channel behavioral mapping, and strategic implementation.

---

## Phase 1: Exploratory Data Analysis (EDA) & Scope Definition
- **Data Hygiene & Preparation:** Handled missing values (such as income imputations) and standardized data types for consistency across all demographic and transactional attributes.
- **Demographic Profiling:** Analyzed customer attributes including education, marital status, income, and family structure to identify initial cohort groupings.
- **Baseline Metrics:** Established baseline distributions for customer lifetime value, total spending, and campaign response rates.

---

## Phase 2: Statistical Correlation & Trend Discovery
- **Product Spending vs. Income:** Discovered a strong positive correlation between customer income and luxury goods like wine (`MntWines`: **0.579**), compared to a weaker correlation with everyday staples like fruit (`MntFruits`: **0.431**).
- **Channel Behavioral Mapping:** Examined how customers utilize different purchasing avenues, revealing strong ties between high-income earners and direct-mail catalogs (`NumCatalogPurchases`: **0.589**) as well as physical stores (`NumStorePurchases`: **0.529**).

---

## Phase 3: Visualizations & Behavioral Mapping
- **Product Spending Comparison:** Mapped luxury versus staple spending correlations to demonstrate how incremental customer wealth shifts toward premium goods.
- **Channel Overlap Matrix:** Structured data comparing web, store, and catalog channels to illustrate how affluent buyers navigate touchpoints.

### Phase 3 Data Tables (Ready for Google Sheets)
1. **Product Spending Correlation Summary:**
   - `MntWines`: 0.579 (Luxury / Discretionary - Primary High-Value Target)
   - `MntMeatProducts`: 0.585 (Mid-Tier / Premium - Secondary Upsell Target)
   - `MntFruits`: 0.431 (Everyday Staple - Retention / Baseline Offer)
   - `MntGoldProds`: 0.326 (Specialty / Niche - Targeted Promotional Add-on)

2. **Purchasing Channel Behavior Matrix:**
   - `NumStorePurchases`: Income Correlation = 0.529 | Wine Correlation = 0.642 | Core omni-channel anchor
   - `NumCatalogPurchases`: Income Correlation = 0.589 | Wine Correlation = 0.635 | High-value direct channel favored by affluent luxury buyers
   - `NumWebPurchases`: Income Correlation = 0.388 | Wine Correlation = 0.542 | Digital touchpoint used across segments

---

## Phase 4: Actionable Insights & Final Deliverables

| Strategy Component | Target Segment / Channel | Recommended Action | Expected Business Impact |
| :--- | :--- | :--- | :--- |
| **Campaign Optimization** | Married + Graduation Demographic (Campaign 4 Focus) | Tailor exclusive promotional bundles and personalized messaging around life milestones. | Higher conversion rates and better ROI on marketing spend. |
| **Catalog Channel Strategy** | Affluent Customers (High Income / Wine Buyers) | Increase direct-mail catalog deployment for high-value product launches and luxury promotions. | Stronger engagement and larger basket sizes among high-income tiers. |
| **Digital & Store Omnichannel** | Moderate Income & General Shoppers | Maintain integrated web and physical store touchpoints. | Balanced cross-channel retention and consistent everyday revenue. |
| **Budget Allocation Summary** | Direct Mail & High-End Focus | Reallocate 60% of discretionary promotional budget to high-value channels (Catalog/Store) targeting top-tier earners. | Maximized profit margins by focusing acquisition cost on high-LTV segments. |

---

## Live Data & Resources
- [Marketing Analysis Master Spreadsheet](https://docs.google.com/spreadsheets/d/1fBHgE_A7MXkUnqdrwC4csV0TwYQ7dueRvqWcQkxnyO8/edit?usp=sharing)
