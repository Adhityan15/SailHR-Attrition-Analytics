# SailHR-Attrition-Analytics
A project from the Google Advanced Data Analytics program. Predicts employee attrition, identifies key turnover drivers, and provides actionable HR insights using Logistic Regression, Decision Tree, and Random Forest models with EDA and feature engineering.


# HR Attrition Prediction and Analytics

A data-driven HR Analytics project to predict employee attrition, uncover key attrition drivers, and recommend actionable strategies to improve retention. This project uses EDA, feature engineering, Logistic Regression, Decision Tree, and Random Forest models.

📌 1. Problem Statement

Employee attrition leads to loss of talent, productivity decline, and high rehiring costs. The goal of this project is to:

Predict which employees are likely to leave

Identify the top attrition factors

Recommend HR interventions backed by data

📌 2. Dataset

HR employee dataset (supervised, classification)

Target variable: left (1 = employee left, 0 = stayed)

📌 3. Project Workflow
Step	Task
1	Data Understanding & Cleaning
2	EDA & Visualization
3	Feature Engineering
4	Model Training (LogReg, Decision Tree, Random Forest)
5	Model Evaluation
6	HR Insights & Recommendations
📌 4. Model Performance (Summary)
Model	Accuracy	Precision	Recall	F1-Score	AUC
Logistic Regression	83%	80%	83%	80%	—
Decision Tree	96.2%	87.0%	90.4%	88.7%	93.8%
Random Forest	Best performer (slightly higher than DT)				
📌 5. Key Insights

✔ Overwork strongly increases attrition
✔ Employees working on too many projects are at high risk
✔ 4+ years tenure employees show dissatisfaction
✔ Long working hours + low reward strongly contributes to exits

📌 6. Recommendations to HR

Limit max projects per employee

Reward or reduce overtime expectations

Consider promotion/engagement plans for 4+ years employees

Make policies on workload, time-off, and overtime explicit and fair

Stop linking best evaluations only to extreme working hours

📌 7. Next Steps (Future Work)

Try model without last_evaluation to check data leakage

Build unsupervised K-Means clustering

Deploy using Flask / Streamlit

📌 8. Tech Stack
Category	Tools
Language	Python
ML	scikit-learn
Visualization	Matplotlib, Seaborn
Notebook	Jupyter
📌 9. How to Run
pip install -r requirements.txt
jupyter notebook

📌 10. License

MIT License.

✅ requirements.txt (add this in repo)
pandas
numpy
matplotlib
seaborn
scikit-learn

✅ .gitignore (add this)
__pycache__/
.ipynb_checkpoints/
models/
data/raw/
