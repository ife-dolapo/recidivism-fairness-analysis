# recidivism-fairness-analysis
A machine learning project using the COMPAS dataset to predict recidivism, analyze fairness across racial groups, and apply explainability techniques like SHAP and LIME to interpret model decisions.
# Recidivism Prediction and Fairness Analysis

## Project Overview

This project explores ethical AI practices in criminal justice by predicting recidivism using the COMPAS dataset. It combines logistic regression modeling with fairness and explainability techniques to evaluate bias across racial groups and interpret individual predictions. The goal is to demonstrate how machine learning can be responsibly applied in high-stakes decision-making.

Key components include:
- Data preprocessing and feature engineering
- Model training and evaluation
- Fairness metrics using Fairlearn
- Explainability using SHAP and LIME
- Ethical analysis and recommendations

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/recidivism-fairness-analysis.git
cd recidivism-fairness-analysis
```
### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r Requirements for recidivism-fairness-analysis.txt
```
### If you're using Google Colab, you can install missing packages inline:
```bash
!pip install lime shap fairlearn scikit-learn pandas matplotlib seaborn
```
### 4. 
Run the Notebook
Open and run the main notebook:
```bash
notebook Assignment 14 - Ethical AI Analysis and Explainability.ipynb
```
File Structure
├── Assignment 14 - Ethical AI Analysis and Explainability.ipynb        # Main notebook with modeling, fairness, and explainability outputs
├── README.md                                                           # Project overview and setup instructions
├── Requirements for recidivism-fairness-analysis.txt                   # Python dependencies

All visualizations (SHAP, LIME, fairness metrics) are embedded directly in the notebook for ease of viewing and reproducibility.

---
Dataset
This project uses the `COMPAS dataset` published by ProPublica. It contains criminal justice data used to assess the risk of recidivism.
To run the notebook:
- Download the dataset (compas-scores-two-years.csv) from the `ProPublica GitHub repository`.
- Place the file in the same directory as the notebook.


