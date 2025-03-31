
# **Bank Marketing Campaign – Subscription Prediction**

## **Overview**
This project explores machine learning methods to predict whether a customer will subscribe to a banking product after being contacted in a marketing campaign. Given the low success rate of previous campaigns, the goal is to improve targeting by focusing on customers most likely to subscribe.  

## **Dataset**
- **Filename:** `bank-full.csv`  
- **Size:** ~41,000 records  
- **Features:** 20 customer-related attributes  
- **Target Variable:** `y` (Binary: "yes" = subscribed, "no" = not subscribed)  

## **Objective**
- Build a **proof-of-concept machine learning model** to predict if a customer will subscribe.
- Ensure **good performance for both classes** (subscribers and non-subscribers).
- Provide insights into which factors contribute to customer subscription.

## **Methodology**
1. **Data Preprocessing:**
   - Handle missing values and categorical data.
   - Perform exploratory data analysis (EDA).
   - Apply feature scaling and selection.

2. **Model Selection:**
   - Compare classification models: Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.
   - Use cross-validation for unbiased performance estimation.

3. **Performance Metrics:**
   - **Accuracy & Precision-Recall:** Ensure high accuracy while handling class imbalance.
   - **ROC-AUC Score:** Evaluate model's ability to distinguish between classes.
   - **Confusion Matrix & F1-Score:** Analyze false positives/negatives.

4. **Final Model & Insights:**
   - Train the best-performing model.
   - Interpret key features influencing subscription decisions.
   - Provide recommendations for marketing strategies.

## **Results** : Refer to the results file 
## **Technologies Used**
- Python  
- Scikit-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn  


## **Requirements**
```
numpy  
pandas  
matplotlib  
seaborn  
scikit-learn  
```

## **Future Improvements**
- Try deep learning models (e.g., Neural Networks).  
- Use advanced feature engineering for better predictions.  
- Deploy the model as an API for real-time predictions.  

This structure ensures that your **GitHub repository** looks professional and is easy to navigate. 🚀  

