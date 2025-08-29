# Deep Learning Approaches for Diabetes Prediction: A Comparative Study of Class Imbalance Techniques with Model Interpretability and Regression Analysis


## About the Dissertation
This repository contains the implementation developed as part of my MSc dissertation at University of Kent.

The primary objective of this dissertation is to investigate how data imbalance and sampling strategies influence the performance of deep learning models for diabetes prediction, while benchmarking against traditional machine learning approaches. The research addresses three key areas: class imbalance handling through undersampling and SMOTE techniques, model interpretability via counterfactual analysis, and regression for continuous health indicators.


## Repository Structure
- **Data Preparation and Exploratory Analysis**  
  - `EDA/` : Exploratory Data Analysis (graphs and statistical summaries)  
  - `Handling of Atypical Values/` : Data cleaning and treatment of atypical values  

- **Models/**  
  - `Counterfactual Analysis/` : Counterfactual explanation analyses using Random Forest 
  - `Oversampling/` : Models trained on oversampled datasets (SMOTE)   
  - `Regression/` : Single and multi-target regression models  
  - `Undersampling/` : Models trained on undersampled datasets  
  - `With Imbalanced Data/` : Models trained on the original imbalanced dataset  



## Installation
All dependencies are listed in `requirements.txt`. Install them using:
```bash
pip install -r requirements.txt
