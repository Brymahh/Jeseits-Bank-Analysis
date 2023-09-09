
![Logo](https://github.com/Brymahh/Jeseits-Bank-Analysis/blob/main/Jeseits.png?raw=true)


# Jeseits Bank Personal Loan Prediction

`Jeseits Bank wants to explore ways of converting its liability customers to personal loan customers. The bank ran a campaign last year for liability customers and showed a healthy conversion rate of over 9% success. Thus the retail marketing department wants to devise campaigns with better target marketing to increase the success ratio with minimal budget.`


## Project Objectives
The dataset "bank-data.csv" comprises information pertaining to 5,000 customers of Jeseits Bank. This dataset encompasses demographic details as well as the responses of these customers to the most recent personal loan campaign. Notably, the data reveals that approximately 9.6% of the customers accepted the personal loan offered during the previous campaign.

As a result, Jeseits Bank is keen on delving into their data to extract valuable insights from their customer base. Their ultimate goal is to develop a predictive model that can estimate the probability of a liability customer purchasing personal loans.

----------------------------------
## Exploratory Data Analysis
- The dataset showed an uneven distribution of the categories in the personal loan column, thus data balancing had to be implemented.
- A Larger percentage of Jeseits customers are undergraduate students resulting in a in a substantial income stream from this segment.
- From the analysis and visuals, campaigns should be tailored towards adult, elders age-category  and also customers in education level 2 and 3, as they exhibited a higher level of responsiveness to personal loan subscriptions in previous campaign.
- Marketing strategies should be infused into Jeseits online banking platforms as a significant proportion of personal loan subscriptions originated from online users.
- Customers without Certificate of Deposit/Security accounts procured personal loans compared to those without. Hence, re-assessment of the processes involved in acquiring these accounts should be done.
- Overall, undergraduate students displayed a lower response rate to personal loan subscriptions. Given Jeseits Bank's substantial customer base in this category, it is advisable to devise loan terms and conditions to cater to students' needs while also considering potential associated risks.

## Conclusion
- For model optimization, the training set had to be balanced utilizing the SMOTE technique ollowed by scaling using the Robust Scaler, which accounts for outliers.
- Among the various algorithms employed, XGBoost yielded the highest F1-score and corresponding accuracy.





## Installation

[Imbalanced-Learn](https://imbalanced-learn.org/stable/references/index.html)

```bash
  pip install imbalanced-learn

```