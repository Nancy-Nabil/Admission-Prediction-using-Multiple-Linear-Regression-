🎓 Admission Prediction using Multiple Linear Regression (From Scratch)
📌 Project Overview
This project implements Multiple Linear Regression from scratch (no scikit-learn) to predict the Chance of Admission of students based on their academic and profile features. The model is built step by step using NumPy and basic Python, including training, evaluation, and visualization.

📂 Dataset
File: Admission_Predict.csv

Features Used:

GRE Score
TOEFL Score
University Rating
SOP (Statement of Purpose strength)
LOR (Letter of Recommendation strength)
CGPA
Research (0 = No, 1 = Yes)
Target Variable:

Chance of Admit (continuous value between 0 and 1)
⚙ Methodology
Data Preprocessing

Removed unnecessary columns (Serial No.)
Checked for missing and duplicate values
Separated independent features (X) and target (y)
Model Implementation (From Scratch)

Created a custom MultipleLinearRegression class:

Implemented Normal Equation to compute regression coefficients:

θ
=
(
X
T
X
)
−
1
X
T
y

Implemented predict() method for new samples

Implemented evaluation metrics: R² and Mean Squared Error (MSE)

Implemented visualization methods (residuals, feature importance, predictions)

Model Training & Evaluation

Trained the model on admission dataset
R² Score: ~0.82
MSE: ~0.004
Visualization showed strong correlation between actual and predicted values
📊 Results & Insights
R² Score: 0.82 → The model explains ~82% of the variance.
MSE: 0.004 → Predictions are close to actual admission chances.
Key Features: CGPA and GRE Score had the strongest influence on predictions.
Visualizations Generated:

Actual vs Predicted scatterplot
Residual plot
Feature importance bar chart

📈 Sample Prediction
GRE	TOEFL	Univ. Rating	SOP	LOR	CGPA	Research	Predicted Chance
330	115	4	4.5	4.0	9.2	1	~0.93
310	105	3	3.0	3.5	8.5	0	~0.74
320	110	4	4.0	4.0	8.8	1	~0.86
🧑‍💻 Built From Scratch
✅ No machine learning libraries (like scikit-learn) were used for training. ✅ Implemented regression equations, metrics, and plots using NumPy and Matplotlib only. ✅ This helps build a deeper understanding of how regression works internally.

📬 Contact
Contact: nancnanbil647@gmail.com
LinkedIn: Nancy Nabil
