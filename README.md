# Machine-Learning---Claim-Predictions-NOVA-IMS-

Project Developed By:
- Pedro Santos
- Diogo Correia
- Oumaima Hfaieh
- Rita Morgadito
- Duarte Miguel

# **Workplace Injury Claim Prediction Project**

Welcome to the **Workplace Injury Claim Prediction Project**, a machine learning solution developed to assist the **New York Worker’s Compensation Board (WCB)** in managing workplace injury claims. This repository contains all resources and implementations for building predictive models, analyzing outcomes, and providing users with an interface for generating personalized predictions.

---

## **Project Overview**

This project focuses on predicting two critical outcomes:
1. **Claim Injury Type**: A multi-classification problem with eight distinct classes, aimed at predicting the type of injury associated with each claim.
2. **Agreement Reached**: A binary classification problem to determine whether an agreement was reached prior to a WCB decision.

To accomplish this, we processed datasets containing over **550,000 resolved claims** and **350,000 unresolved claims** with severe class imbalance. The methodology incorporates data preprocessing, feature engineering, model training, and the development of an interactive interface.

---

## **Key Components**

1. **Main Notebook: Claim Injury Type**  
   - Contains the complete workflow for preprocessing, feature engineering, model training, and evaluation of the multi-classification model.  
   - The best-performing model, **XGBoost**, achieved a **Kaggle score of 0.46** (F1 Macro).

2. **Agreement Reached Notebook**  
   - Focuses on predicting whether an agreement was reached, using a similar methodology with slight modifications in feature selection and preprocessing.  
   - The **CatBoost Classifier** emerged as the top-performing model, achieving a **Macro F1 score of 0.7** and **0.45 F1 Standard Score** for the minority class.

3. **Open-Ended Section: HTML and Interactive Interface**  
   - Two interactive tabs were created using **HTML, CSS, JavaScript**, and **Flask**.  
   - Users can input claim details and receive predictions for both target variables via a simple interface.  
   - A **short video** explains the interface and demonstrates its functionality.

---

## **How to Use the Repository**

1. **Notebooks**:
   - Use the `Claim_Injury_Type_Notebook.ipynb` for the multi-classification workflow.
   - Use the `Agreement_Reached_Notebook.ipynb` for the binary classification workflow.

2. **Interface**:
   - The interactive interface files (`app.py`, `index.html`, `ag.html`) are in the `interface/` directory.
   - Run the interface locally using Flask to generate predictions.

3. **Video Tutorial**:
   - Refer to the **video file** in the repository for a quick demonstration of the interface.

---

## **Requirements**
- Python 3.8+
- Libraries: `scikit-learn`, `XGBoost`, `CatBoost`, `Flask`, `pandas`, `numpy`, `joblib`


---

This project showcases the potential of machine learning in optimizing workplace claim management, offering scalable solutions while maintaining user-friendly accessibility.

## **DATA**
- Could not upload here since it is too big.
- In need of the data, contact me.
