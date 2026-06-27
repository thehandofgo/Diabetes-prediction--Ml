# Diabetes-prediction--Ml
Diabetes prediction using ML models (SGD, Random Forest, Gradient Boosting) with threshold tuning and evaluation using ROC-AUC and PR-AUC.


📊 Key Visualizations
ROC Curve Comparison (SGD vs RF vs GBoost)
Precision-Recall Curve Comparison
Threshold vs Precision/Recall Tradeoff Plots
🧠 Key Insights
Default threshold (0.5) is not optimal for medical classification problems
Lower thresholds significantly improve recall, which is critical for early disease detection
Gradient Boosting performed best in capturing positive cases (diabetes patients)
Random Forest achieved best balance at threshold = 0.30
Model selection should prioritize recall over accuracy in healthcare settings
🏥 Real-World Impact

This system can support:

Early diabetes screening
Clinical decision support systems
Risk stratification in healthcare environments

The model is optimized to reduce false negatives, ensuring high-risk patients are not missed.

🛠️ Tech Stack
Python 🐍
Pandas / NumPy
Scikit-learn
Matplotlib / Seaborn
Machine Learning Pipelines
🚀 Future Improvements
Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
Feature selection optimization
SHAP for model interpretability
Deployment using Streamlit or Flask API
Real-time prediction dashboard

👨‍💻 Author

Solomon Nyarko
Data Science | Machine Learning | Healthcare Analytic
