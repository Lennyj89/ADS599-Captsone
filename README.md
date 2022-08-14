# ADS599-Predicting Woman, Infant, and Children Participant Churn

This project is a part of the ADS599 (Capstone) course in the Applied Data Science Program at the University of San Diego.

**Project Status: Completed**

## Project Overview

Woman, Infant, and Children (WIC) is a company which aids lower income family’s get the nutrition they need. Due to the company’s importance in helping millions across the United States, they wish to lower their participant churn rate to ensure as many families as possible are benefiting from the program and they are reaching everyone who needs their support. To achieve this goal, machine learning models were used to help predict when a customer might stop using the program. Once WIC provided data on their current participants from South Dakota, feature engineering and data cleaning was performed so the data would be optimal for five unique machine learning models: Naïve Bayes, XGBoost, Logistic Regression, Neural Net, and Random Forest. It was found over 90% of participants in the data were no longer using WIC, meaning the data was highly imbalanced. This was accounted for with synthetic minority oversampling technique (SMOTE) and random under sampling to produce an equal number of both churners and non-churners in the training data set. Choosing the best model was done by examining accuracy and the area under curve (AUC). Random Forests performed the best with an accuracy of 93% and AUC of 0.95. This level of accuracy was achieved after multiple rounds of hyper tuning to ensure the most optimal parameters were selected. Once the model is in deployment, the plan is to contact those who are predicted to churn with information campaigns on how they can best utilize the program to lower the chance of their departure from the program.

### Partners

- Leonard Littleton (https://github.com/Lennyj89)
- Andrew Zazueta (https://github.com/AndrewZazueta)

### Methods Used

- Exploratory Data Analysis
- Data Preprocessing
- Resampling Techniques
- Hyperparameter Tuning
- Predictive Modeling

### Technologies

- Python
- SQL
