# Portuguese Bank Marketing Prediction

This project involves analyzing and modeling a real-world marketing dataset provided by a Portuguese bank. The objective is to predict whether a client will subscribe to a term deposit based on various personal, social and campaign-related features.


## Problem Statement

Develop a predictive model that helps the marketing team identify which customers are most likely to subscribe to a term deposit, enabling better-targeted campaigns.


## Dataset Information

- **Source**: UCI Machine Learning Repository (Used via PRCP-1000 project)
- **File Used**: `bank-additional-full.csv`
- **Records**: ~41,000
- **Features**: Demographics, contact information, past campaign outcomes and macroeconomic variables.
- **Target Variable**: `y` – whether the client subscribed to a term deposit (`yes` or `no`)

📎 [Original Dataset Link](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1000-ProtugeseBank.zip)


## 🔍 Key Steps Performed

- Data cleaning, validation and preprocessing
- Feature engineering (binary features, encoding, scaling)
- Exploratory Data Analysis (EDA) with visualizations
- Model building: Logistic Regression, Random Forest and more
- Model evaluation: Accuracy, F1-score, ROC-AUC
- Business insights and actionable recommendations for the marketing team


## ⚙️ Tools & Libraries Used

- Python (Jupyter Notebook)
- `pandas`, `numpy` – data manipulation  
- `matplotlib`, `seaborn` – visualization  
- `scikit-learn` – ML modeling and evaluation  
- `Power BI` / `Tableau` – for external dashboarding  
- `Git` – version control


## Model Performance

| Model               | Accuracy | F1 Score | ROC AUC |
|--------------------|----------|----------|----------|
| Logistic Regression| 89%      | 0.81     | 0.84     |
| Random Forest      | 91%      | 0.85     | 0.87     |


## Challenges Faced

- Handling highly imbalanced classes in the target variable  
- Deciding whether to include the `duration` feature (since it's not available before calls)  
- Encoding categorical features with many categories (e.g., `job`, `education`)  
- Avoiding data leakage and ensuring realistic model performance


## Business Recommendations

- Focus marketing efforts on segments with higher predicted conversion probability  
- Consider previous campaign outcomes (`poutcome`) and call duration patterns  
- Use models to refine call targeting strategy and reduce cost-per-acquisition


## Author

**Dev Dharmendra Modi**  
📧 devmodi0403@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dev-modi7)

