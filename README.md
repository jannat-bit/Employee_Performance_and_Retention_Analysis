Employee Performance & Retention Analysis
This project analyzes employee performance and attrition trends using probability, statistics, machine learning, and deep learning.
The dataset contains employee information such as demographics, salary, years at the company, performance scores, and attrition status.
The goal is to:
Understand employee performance and retention patterns
Predict attrition (classification task)
Predict performance scores (regression task)
Generate actionable insights and recommendations
Required Libraries
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow / keras
📊 Analysis Workflow
Exploratory Data Analysis (EDA)
Descriptive statistics
Correlation heatmap
Boxplots to detect outliers
Statistical Analysis
Probability of attrition by department & performance band
Hypothesis testing (ANOVA on performance across departments)
Machine Learning Models
Logistic Regression & Random Forest → Attrition Prediction
Linear Regression → Performance Score Prediction
Deep Learning Models
Feedforward Neural Network → Performance Score Prediction
Neural Network Classifier → Attrition Prediction
Reporting & Insights
Key drivers of attrition & performance
High-risk departments
Recommendations for retention strategies
📈 Example Outputs
Attrition Confusion Matrix (Logistic Regression)
Performance Prediction: Actual vs. Predicted Plot
Correlation Heatmap of Key Features
Artifacts and insights are saved in the artifacts/ folder.
🧠 Key Learnings
Data preprocessing: scaling numeric features & encoding categoricals
Probability & Bayes’ Theorem in HR analytics
Hypothesis testing with ANOVA
Classification & regression models for business problems
Applying deep learning with Keras for tabular data
🚀 Next Steps
Add SHAP/feature importance for explainability
Build an interactive dashboard with Streamlit or Dash
Extend dataset with more employees and features
