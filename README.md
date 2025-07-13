# MSCS-634-B01-Lab1

## Author: Pawan Pandey

### Dataset
This analysis uses the Credit Card Fraud Detection dataset from Kaggle. It contains anonymized features from European credit card transactions. I haven't included the dataset in this repository as it's quite large in size for github. The link for the dataset is: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

### Objectives
- Visualize transaction patterns.
- Preprocess data by detecting outliers, handling skewness, and scaling.
- Perform statistical analysis to better understand fraudulent behavior.

### Key Insights
- Fraud cases are rare but show distinct patterns in transaction time and amount.
- Most transactions are low in amount, and fraud tends to cluster around smaller sums.
- High correlation among PCA features makes dimension reduction possible for further ML tasks.

### Challenges
- Imbalanced dataset with only ~0.17% fraud cases.
- Many features are anonymized (PCA), limiting intuitive analysis.

### Screenshots
All screenshots are located in the `/screenshots` folder.