# Home-Credit-Default-Risk
## Business Problem
  Business Problem: This project aims to build a predictive model for Home Credit that identifies high-risk loan applicants using alternative data. The business faces the dual challenge of minimizing defaults while expanding financial inclusion to underserved populations with limited credit history. This EDA notebook will explore data quality, identify predictive patterns in applicant behavior and external credit sources, and investigate class imbalance to guide our modeling strategy for this binary classification problem.
## Group solution to the business problem
  The team built Multiple models—including Logistic Regression, Naive Bayes, Random Forest, and XGBoost—were trained and evaluated using 5-fold cross-validation and AUC as the performance metric. 
XGBoost emerged as the best model and was integrated into a scoring pipeline that outputs a risk probability and recommends an action (Approve/Review/Decline). This solution reduces default rates and improves the consistency of lending decisions.
## Contribution to the project
### Data Cleaning
* Identified and handled missing values using appropriate imputation strategies.
* Standardized and validated key features such as income amounts, credit history fields, and categorical variables.
* Detected and removed inconsistent or duplicated records to ensure data integrity.
### Random Forest Model Development
* Built a Random Forest classifier as one of the core baseline models.
* Tuned hyperparameters (number of trees, max depth, mtry) to improve AUC.
* Evaluated performance using cross-validation and compared results against other models.
* Provided feature importance visualizations that helped the group interpret key risk drivers.
* Helped confirm that while Random Forest performed well, XGBoost outperformed it and should be used as the final model.
# The business value of the solution
* **Reduced default rates**, by accurately flagging high-risk applicants.
* **Lower annual losses**, drop from an 8.1% to 2.9% default rate.
* **More approvals for good customers**, increasing revenue while maintaining risk control.
* **Faster and more consistent decisions**, improving customer experience.
* **Better regulatory compliance through documented**, explainable risk assessments.
# Difficulty
* **Large and complex dataset** resulted in long model training times.
* **Potential biases** in the data needed to be considered to ensure fairness.
* **Feature engineering** was challenging because many variables were highly correlated or nonlinear.
* **Model selection** required extensive testing and comparison across multiple algorithms to find the best performer.
# Take Away
* How to clean and prepare real-world financial data with extensive missingness and irregularities.
* How Random Forest works, including bootstrapping, tree aggregation, and feature importance.
* How to compare models using metrics such as AUC, accuracy, precision/recall, and cross-validation.
* The importance of balancing predictive accuracy with business interpretability and fairness.
* How machine-learning models can be integrated into real-time decision workflows to create tangible business value.
