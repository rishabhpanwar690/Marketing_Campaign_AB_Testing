# Marketing_Campaign_AB_Testing

📊 A/B Testing & Campaign Performance Analysis
📌 Project Overview

This project analyzes and compares marketing campaign performance using A/B testing, statistical hypothesis testing, and regression modeling.

The objective is to determine which advertising platform performs better in terms of conversions, clicks, and overall effectiveness, and to provide data-driven recommendations for business decision-making.

🎯 Business Objective

Evaluate campaign performance across advertising platforms.

Identify statistically significant differences in conversion rates.

Estimate expected conversions based on click data.

Provide actionable insights to improve marketing ROI.

❓ Research Question

Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness?

🧰 Tech Stack & Libraries

Python

pandas

numpy

matplotlib

seaborn

scipy

scikit-learn

statsmodels

🔎 Project Workflow
1️⃣ Data Collection & Preparation

Imported campaign performance dataset.

Cleaned missing values and validated data consistency.

Verified data types and removed anomalies.

Prepared data for statistical analysis.

2️⃣ Exploratory Data Analysis (EDA)

Compared conversions across campaigns.

Analyzed click-to-conversion behavior.

Visualized daily conversion distributions.

Evaluated overall campaign performance trends.

Key focus:

Conversion rates

Click volumes

Distribution patterns

Performance over time

3️⃣ A/B Testing & Hypothesis Testing
Hypothesis Setup

Null Hypothesis (H₀): No significant difference in conversions between campaigns.

Alternative Hypothesis (H₁): One campaign generates significantly higher conversions.

Significance Level: α = 0.05

Statistical Testing

Conducted appropriate statistical tests to compare means.

Evaluated p-values to determine statistical significance.

Interpreted results to validate or reject H₀.

Key Result

Campaign B achieved a higher conversion rate with statistical significance (p < 0.05).

4️⃣ Regression Analysis

Objective:

Estimate expected conversions based on number of clicks.

Steps:

Built a linear regression model.

Evaluated model performance using:

R² score

Mean Squared Error (MSE)

Interpreted relationship between clicks and conversions.

Outcome:

Established predictive relationship between click volume and conversion output.

Enabled forecasting of expected conversions.

5️⃣ Performance Comparison

Compared:

Total conversions

Conversion rate

Campaign lift

Trend behavior over time

Calculated conversion lift between platforms to quantify impact.

6️⃣ Business Insights

Campaign B outperformed Campaign A in conversion rate.

Statistical evidence supports rolling out Campaign B.

Increasing clicks positively impacts conversions (as shown by regression model).

Data-driven optimization can improve ROI without increasing ad spend.

⚠️ Limitations

Limited sample size may impact statistical power.

No user segmentation (new vs returning users).

External factors (seasonality, targeting changes) not controlled.

Linear regression assumes linear relationship.

🚀 Future Improvements

Perform power analysis before experimentation.

Segment user groups for deeper insights.

Test additional campaign variants (multi-arm bandit approach).

Incorporate time-series modeling for seasonality adjustments.

Add cost-per-acquisition and ROI analysis.
