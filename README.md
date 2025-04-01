 # **PCOS-EnsembleX: A Machine Learning Classifier for PCOS Detection**  

## **Overview**  
PCOS-EnsembleX is an advanced machine learning classifier designed to predict **Polycystic Ovary Syndrome (PCOS)** with high accuracy. This project implements **Random Forest (RF), XGBoost, and LightGBM** models, along with an **ensemble learning approach** combining all three.  

## **Modeling Approach**  
To ensure robust classification, the following machine learning models were trained and tested:  
✅ **Random Forest (RF)**  
✅ **XGBoost (XGB)**  
✅ **LightGBM (LGBM)**  
✅ **Ensemble Model (Voting Classifier combining RF, XGB, and LGBM)**  

## **Data Balancing with SMOTE**  
Since PCOS datasets are often imbalanced, **SMOTE (Synthetic Minority Over-sampling Technique)** was applied to handle class imbalance and improve model generalization.  

## **Performance Metrics**  
All models achieved **100% accuracy** on the test set, with precision, recall, and F1-scores all reaching 1.00:  

```
              precision    recall  f1-score   support

           0       1.00      1.00      1.00       160
           1       1.00      1.00      1.00        40

    accuracy                           1.00       200
   macro avg       1.00      1.00      1.00       200
weighted avg       1.00      1.00      1.00       200
```
## **Future Improvements**  
- Explore **Stacking Classifier** for better generalization.  
- Implement **SHAP (SHapley Additive exPlanations)** for model interpretability.  
- Deploy the model as a **web app using Flask or Streamlit**.  
