# Market A/B Testing Analysis

## Overview
This project evaluates the effectiveness of a digital advertising campaign using A/B testing and machine learning. By analyzing user engagement and conversion trends, we provide data-driven recommendations to optimize ad placement and maximize return on investment (ROI).

## Business Insights
- **Ad Timing Matters**: Customers are more likely to convert when exposed to ads on **Monday and Tuesday**. This suggests that targeting users at the beginning of the week leads to higher engagement.
- **Campaign Success Confirmation**: A statistical **Z-proportion one-tailed test** at a 5% significance level confirms that the ad campaign was successful.
- **Data Integrity**: The dataset was thoroughly validated—no duplicate users, missing values, or unexpected data anomalies were found.
- **Machine Learning Prediction 🤖**: A predictive model was trained to estimate the probability of a user converting after seeing an ad. The model achieved a strong **AUC score of 0.87**, demonstrating its efficacy in distinguishing between likely and unlikely converters. Additionally, a **ROC curve graph** is included in the notebook to visually represent the model's performance.

## Key Considerations
- **High False Positive Rate 🚨**: The model generates a large number of false positives, meaning it predicts many users will convert when they actually won’t. However, given that the cost of targeting an unlikely converter is minimal compared to the potential gain, this trade-off can be acceptable.
- **Strategic Opportunity 💡**: Businesses can use the model to **expand ad reach** while still maintaining cost-effectiveness, capitalizing on possible but less probable conversions.

## Business Benefits
### 1. Increased Revenue Potential
By **reallocating ad spend** to high-conversion days (Monday and Tuesday), businesses can maximize sales while reducing inefficient ad impressions.

### 2. Cost Optimization
Reducing ad spend on low-conversion days (e.g., later in the week) helps optimize marketing budgets, ensuring higher efficiency in campaign execution.

### 3. Data-Driven Decision Making
With solid statistical backing, businesses can **confidently implement strategic changes** without relying on assumptions, minimizing risk and uncertainty.

### 4. Smarter Targeting with AI 🎯
Leveraging machine learning enables **better audience segmentation**, allowing businesses to tailor their ad strategy dynamically based on predictive analytics.

## Next Steps
- **A/B Testing Refinement**: Conduct additional tests to refine targeting by user demographics and device types.
- **Further Model Optimization**: Explore ways to reduce false positives without compromising the ability to identify high-value users.
- **Ad Frequency Adjustment**: Experiment with different ad frequency levels to find the optimal exposure rate per user.

## Conclusion
The analysis highlights a **clear opportunity to improve conversion rates** through better ad scheduling and machine learning insights. By leveraging data-driven strategies, businesses can achieve higher ROI, better engage their audience, and make informed advertising decisions 📊🚀.

---
For more details, refer to the Jupyter Notebook containing the full analysis, statistical validation, and machine learning implementation, including the **ROC curve visualization**.

