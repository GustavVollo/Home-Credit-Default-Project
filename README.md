# Home Credit Default Project

- Home Credit aims to provide credit services to unbanked and underbanked groups, traditionally seen as high-risk due to lack of conventional credit history. The company uses predictive analytics to improve risk assessment and ensure fair credit access. This strategy is in line with their goal to reduce loan defaults while including those usually excluded from the financial system.
## Predictive model
- Our predictive model significantly impacts loan applicant assessment by precisely categorizing them using over 356,000 client records. This approach reduces default risk and provides credit access to applicants without traditional financial histories. It's a key strategy for sustainable default rate reduction and fostering economic resilience in emerging markets. Additionally, it will ultimately help Home Credit's balance as they increase financial inclusion while balancing default risk. 
## XGBoost
- Our team used the XGBoost algorithm for its high accuracy in predicting outcomes, achieving an impressive accuracy score of over 0.92 and a Kaggle score above 0.76, while also sparking a discussion on balancing loan approvals and minimizing defaults. However, the model initially underpredicted defaults compared to the actual 8% rate in our training data, highlighting a need to better represent default cases and manage the trade-off between precision and minority class representation. Our analysis identified key variables that forecast loan repayment, guiding us to focus on collecting the most predictive data for future loan processing.
## Our process
- My role in the project involved aiding in coding, drafting the report, and formulating business recommendations. My background in finance was influential in providing relevant and impactful advice for Home Credit.

- We faced several challenges, including managing big data and extended processing times. Additionally, we grappled with issues in feature imputation, which led to alterations in the distribution of our features. Another obstacle was the decision not to consolidate data due to inconsistencies in ID matches and disorganized data attributes.

- This project provided valuable insights into the application of data analytics in real-time business contexts. The experience involved a challenging yet enlightening journey through handling large datasets with significant missing data, identifying key features, and selecting the optimal model to devise a business solution. Throughout this process, maintaining a business-centric approach was a critical and continuous test of focus and strategy. This all summarizes a project that was very fun but also extremely challenging. 

- Our project came to conlude that we need to balance financial inclusion with risk by dynamically adjusting the thresholds. The following graph outlines how increase in inclusion also leads to increase in risk.
<img src="/Capture2.JPG?raw=true"/>
