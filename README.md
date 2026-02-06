# heart-disease-diagnostic-classifier
💓 Heart Disease Diagnostic Assistant (Classification)

📖 Introduction
Heart disease remains a leading cause of mortality worldwide. This project focuses on building a Predictive Risk Stratification tool using Logistic Regression. By analyzing 13 clinical features—such as cholesterol levels, chest pain type, and maximum heart rate—the model provides an automated risk assessment to help doctors prioritize urgent cases.

🎯 Project Objectives
Develop a binary classifier to distinguish between "Healthy" and "High-Risk" heart disease profiles.

Implement Feature Scaling (Standardization) to ensure mathematical fairness across different medical units (e.g., Age vs. Cholesterol).

Prioritize Recall over Accuracy to minimize "False Negatives" in a clinical setting.

🛠️ The Technical Workflow
Data Inspection: Checked for class balance (Found: 526 Sick vs. 499 Healthy).

Preprocessing: Applied StandardScaler to normalize the data range.

Modeling: Used LogisticRegression with increased iterations (max_iter=1000) for model convergence.

Evaluation: Analyzed results using a Confusion Matrix and Classification Report.

📊 Results & Medical Interpretation
Recall (Class 1): 87% – The model successfully caught nearly 9 out of 10 heart disease cases.

Accuracy: 80% – A strong baseline for clinical triage.

Confusion Matrix Insight: The model prioritize safety; it would rather trigger a "False Alarm" (False Positive) than miss a sick patient (False Negative).

🚀 Business & Clinical Impact
Efficiency: Reduces the manual workload for cardiologists by identifying high-risk patients instantly.

Safety: The high recall score ensures that fewer high-risk patients are overlooked during initial screenings.
