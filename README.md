BNPL-Financial-Wellbeing-Classification

📌 Project Overview

Can we predict "Buy-Now Pay-Later" (BNPL) usage based on a student's financial stability? This end-to-end data science project investigates the intersection of Fintech and Behavioral Economics. Using a custom-built synthetic data engine, I developed a classification framework to identify the probability of BNPL adoption within student demographics, focusing on the resulting risks of cyclical debt and financial vulnerability.

🛠️ Tech Stack & Methodology

Language: Python 3.x

Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib

Modeling: Logistic Regression (Binary Classification)

Metrics: McFadden’s Pseudo R², ROC/AUC, Confusion Matrix, Accuracy Scores

Data Engineering: Synthetic Data Generation (Normal Distributions & Correlated Derived Variables)

🏗️ The Project Lifecycle

Unlike standard datasets, this project documents the entire research pipeline:

Planning & Ethics: Detailed research plan covering k-anonymity, GDPR compliance, and public-good objectives.

Synthetic Data Generation: A Python-based engine (Generator.ipynb) that simulates realistic student financial behaviors using Likert-scale distributions.

Statistical Analysis: Logistic regression implementation (Data Analysis.ipynb) to determine the predictive power of financial stability on service usage.

AI-Assisted Reflection: A transparent "AI Reflection" document detailing how generative AI was used for peer-review and iterative improvement of the research plan.

📊 Performance & Findings

The model evaluated the relationship between an individual's "Financial Stability Score" and their likelihood of being a BNPL user.

Key Visualizations: Includes ROC Curves and Confusion Matrices to validate the sensitivity/specificity of the classifier.

Impact: The research highlights the potential for financial institutions to use classification models for more ethical service delivery and risk identification among young adults.

📂 Repository Structure

Data Analysis.ipynb: Preprocessing, model training, and evaluation.

Generator.ipynb: Script for simulating the synthetic dataset.

docs/Context.pdf: Deep-dive into the literature and research gap.

docs/Reflection.pdf: A critical evaluation of the project's ethics and AI integration.

docs/Figures.pdf: High-resolution visualizations of the model's output.

🚀 How to Run

Generate Data: Run Generator.ipynb to create the synthetic_financial_wellbeing.csv.

Run Analysis: Open Data Analysis.ipynb to execute the model and view performance metrics.
