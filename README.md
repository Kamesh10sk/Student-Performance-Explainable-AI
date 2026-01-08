# Student-Performance-Explainable-AI
Explainable AI system for predicting student performance and early academic risk detection

Overview of the Project

This project outlines an intelligent and explainable machine learning system for predicting academic performance among high school students. This system will predict grades for individual students, identify at-risk students early, detect subject-wise weaknesses, and provide personalized learning recommendations based on behavioral and academic data.
Key Features
- Individual student-wise grade prediction
Early detection of academic risk (High / Medium / Safe)
Subject-wise identification of weakness.
• Explainable AI using feature importance
Learning style clustering

- Linear Regression for what-if analysis
Fairness-aware feature selection
Machine Learning Models
- Random Forest Regressor: primary prediction
Linear Regression - What-if Simulation
K-Means Clustering - Learning style analysis
Dataset 
Custom high school student dataset including:
- Subject-wise marks
- attendance percentage
- Study hours
- Assignment completion
- Sleep hours
Unwanted and biased features were removed in order to improve fairness and accuracy.

Tech Stack
- Python
- Pandas, NumPy
- scikit-learn
Matplotlib, Seaborn
Results - Achieved ~1.08 MAE after feature refinement - Improved fairness and interpretability - Generated human-readable output for academic decision support ## How to Run ```bash pip install -r requirements.txt python main.py
