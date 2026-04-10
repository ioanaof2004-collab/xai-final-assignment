Explainable AI Final Assignment

# Topic
Interactive explanations and trust in AI through different user interfaces.

# Project overview
This project investigates how different explanation formats influence the understanding and trust of AI predictions in a healthcare setting.

The use case is heart disease prediction using the Heart Disease dataset. A Random Forest model is trained, and two explanation methods are applied:
- SHAP (feature importance explanations)
- Counterfactual explanations 

# Main files
- Final_EXP_AI.ipynb – main notebook
- heart.csv – dataset
- requirements.txt – required libraries

# Installation
Required packages:

pip install -r requirements.txt

# How to run
1. Open the notebook:
   jupyter notebook
2. Run all cells in order.

# What the code does
- Loads dataset
- Trains model
- Generates SHAP explanations
- Generates counterfactual explanations
- Compares explanation methods
