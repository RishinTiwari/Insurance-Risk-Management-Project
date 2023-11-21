Predictive Modeling for Insurance Company Profitability


Overview
This repository contains a comprehensive analysis and predictive
modeling approach for insurance companies aiming to assess the risk of
business bankruptcy. Leveraging data from the Taiwan Economic
Journal spanning 1999 to 2009, the dataset encompasses 96 columns and
6280 observations, providing valuable insights into various financial
metrics.
Objectives
1. Assist Insurance Companies: Predict the likelihood of a company
going bankrupt to aid insurance companies in making informed
decisions about offering coverage.
2. Enhance Business Decision-Making: Provide existing insurance firms
with data-driven insights to optimize strategic decisions and minimize
risks.
3. Fraudulent Bankruptcy Detection: Develop models to detect and
prevent fraudulent bankruptcy claims, safeguarding insurance companies
from financial losses.
4. Economic Market Stability Prediction: Contribute to predicting
economic instability in the market, enabling proactive measures and risk
mitigation strategies.
5. Customer Reevaluation and Strategy Planning: Reevaluate current
customers and devise strategies to overcome potential impacts on the
insurance business.
Dataset Characteristics
- Target Variable: Bankrupt (1 if the company is going bankrupt, 0 if not)
- Key Features:
- Net Income to Total Assets
- Cash Flow to Liability
- Retained Earnings to Total Assets
- Total Asset Growth Rate
- Operating Profit Rate
- Cash Flow Rate
- Cash Flow to Sales
- Cash Reinvestment %
- Cash/Current Liability, and more.
Business Scenario
The insurance company offered coverage to 6800 firms, with 220
eventually going bankrupt. The insurance premium is $1000, and if a
firm goes bankrupt, the company faces a loss of $49000 ($50000 payout
- $1000 premium). The "null model" approach on the remaining 50,000
customers would result in a staggering loss of $79,264,705.88.
Modeling Approach
After exploring Decision Trees, Random Forest, and K-NN, the team
identified Random Forest as the optimal model with a recall value of
96.67%. Using default parameters, the expected total profit for the
insurance company is estimated at $442,377,450.98.
Addressing Data Imbalance
Acknowledging the significant class imbalance in bankrupt companies,
this repository aims to explore techniques to mitigate the negative
effects of an unbalanced dataset. By doing so, there is an opportunity to
develop a more robust and profitable predictive model for the insurance
company.
Contents
1. Data Exploration and Preprocessing: Jupyter notebooks detailing the
exploration and preparation of the dataset.
2. Modeling: Implementation of various models, with a focus on
Random Forest, along with hyperparameter tuning.
3. Evaluation: Assessment of model performance, including confusion
matrices, recall values, and profit calculations.
4. Imbalance Mitigation: Strategies and techniques to address the
imbalance in the dataset.
5. Recommendations: Insights and recommendations for insurance
companies based on the analysis.
Note: This repository serves as a comprehensive resource for insurance
professionals, data scientists, and researchers interested in predictive
modeling for bankruptcy risk assessment.
