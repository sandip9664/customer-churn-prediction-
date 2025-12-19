# customer-churn-prediction
Project Title: Customer Churn Prediction & Retention Strategy

Description: Developed a robust machine learning model to predict customer churn, enabling proactive retention strategies. Utilized a comprehensive dataset of customer demographics, engagement metrics, and historical complaint data to identify key churn drivers.

Key Contributions & Techniques:

Data Preprocessing: Cleaned and preprocessed raw customer data, including handling missing values in the 'complaint_type' column by identifying and analyzing the distribution of existing complaint types. Dropped irrelevant identifiers such as customer_id.
Exploratory Data Analysis (EDA): Conducted in-depth EDA to understand data distributions, identify correlations, and visualize categorical and numerical features using histograms, box plots, and count plots. Analyzed feature correlation through a heatmap to understand relationships between variables.
Feature Engineering & Scaling: Applied OneHotEncoder for categorical features and StandardScaler for numerical features to prepare data for machine learning models, ensuring optimal performance.
Model Development: Implemented and evaluated multiple classification algorithms, including Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and XGBoost Classifier, to predict customer churn.
Model Evaluation & Optimization: Achieved competitive accuracy scores, with the Random Forest Classifier demonstrating strong performance (approximately 89.80% accuracy on the test set). Further optimized the Random Forest model using GridSearchCV for hyperparameter tuning, identifying optimal parameters to maximize prediction accuracy (Best CV Accuracy: 0.89825).
Impact: The developed model provides actionable insights for identifying at-risk customers, allowing the business to implement targeted interventions and improve customer retention rates.
Tools & Technologies: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost.
