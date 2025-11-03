Customer Churn Analysis Summary
1. Dataset Overview

The dataset comprises 7,043 customer records and 21 attributes, including demographics (gender, age group), service subscriptions, contract details, billing preferences, and churn status.
All missing or blank entries in the TotalCharges column were replaced with 0 and converted to float for numerical consistency.
No duplicated or null records were found, ensuring clean data for analysis.

Key Stats:
Total records: 7,043
Numeric fields: tenure, MonthlyCharges, TotalCharges
Average tenure: 32.37 months
Average monthly charges: $64.76
Average total charges: $2,279.73

2. Churn Distribution
Churned customers: 26.54%
Retained customers: 73.46%
This implies that roughly 1 in 4 customers discontinued the service — a significant retention concern that warrants detailed behavioral analysis.

3. Demographic Analysis
Gender-wise Churn
Male churn: ~26%
Female churn: ~27%
Churn percentages are nearly identical across genders, confirming gender has no substantial impact on customer attrition.
Senior Citizens
Senior citizens (16% of total customers) show ~42% churn rate.
Non-seniors (84%) have a much lower churn rate of ~24%.
Elderly customers are nearly 1.7× more likely to leave, indicating usability, support, or pricing may not align with their expectations.

4. Tenure Analysis
Customer tenure has a strong inverse relationship with churn:
Tenure < 6 months: Churn ≈ 55–60%
Tenure between 6–24 months: Churn drops to around 30%
Tenure > 24 months: Churn falls below 10%
This suggests that most churn happens within the first few months of service, often due to dissatisfaction or unmet expectations during onboarding.

5. Contract Type
Contract length directly affects churn probability:
Month-to-Month contracts: 43% churn
One-year contracts: 11% churn
Two-year contracts: 3% churn
This clearly indicates that long-term contractual commitment is the strongest predictor of retention.
Month-to-month customers are 14× more likely to leave than two-year customers.

6. Internet and Service Usage Patterns
Internet Service
Fiber optic users: ~42% churn
DSL users: ~19% churn
No internet service: ~7% churn
Customers using fiber optic connections churn at double the rate of DSL users, likely due to performance or cost-related dissatisfaction.
Additional Services
Across all customers:
Online security not subscribed: 74% churners fall in this group.
Tech Support not subscribed: 72% churners.
Device Protection not subscribed: 65% churners.
Customers lacking value-added services like security or support show significantly higher churn, implying these add-ons contribute to loyalty.

7. Payment and Billing Preferences
Payment method has a clear behavioral impact:
Electronic check: 45% churn
Mailed check: 15% churn
Bank transfer (automatic): 10% churn
Credit card (automatic): 12% churn
Customers using manual payment methods (electronic checks) are 3–4× more likely to leave than those using automatic recurring payments.
Additionally:
Paperless billing users: 35% churn
Non-paperless billing users: 20% churn
Electronic billing might correlate with a more transient or experimental user base — possibly short-term subscribers testing the service.

8. Monthly Charges vs. Total Charges
High monthly charge (> $90): 38–40% churn
Low monthly charge (< $50): <15% churn
High total charges (long-term customers): extremely low churn (<5%)
This aligns with the tenure and contract findings — higher total engagement over time means higher satisfaction and loyalty, while expensive month-to-month plans drive churn.

10. Strategic Recommendations
Encourage longer contracts: Offer discounts or loyalty points for 1–2 year commitments.
Bundle support and protection services: Increase adoption of Online Security and Tech Support packages.
Migrate users to auto-pay systems: Incentivize card or bank-based automatic payments to improve retention.
Target early churn prevention: Focus retention campaigns on customers in their first 3–6 months.
Analyze fiber optic dissatisfaction factors: Investigate network reliability or pricing gaps in that segment.
