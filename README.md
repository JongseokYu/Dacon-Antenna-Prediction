# Dacon-Antenna-Prediction

[LG AI Research] AI Competition of Antenna Performance Prediction for Self-driving Sensors
: Aiming to predict product defects through correlation analysis between product processing data and product performance and maximize yield

- Develop a new derivative variables through combining variables with learned domain knowledge and reflect significant variables to the model, considering feature importance, subset selection and factor analysis results
- Build prediction models with Light GBM, XGBoost and Random Forest and figure out the optimal hyper-parameters using K-folds Cross Validation and Optuna methods
- Enhance predictive performance by adapting Ensemble methods to three models above(Light GBM, XGBoost, and Random Forest) and weight based on Attention Score(reference: 'Attention is All you Need') for the best combination of models

: Competition explanation link
https://dacon.io/competitions/official/235927/overview/description
