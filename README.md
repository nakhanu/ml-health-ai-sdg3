# 🧠 Predicting Diabetes Using Supervised Learning  
### Supporting SDG 3 – Good Health and Well-being

---

## 📍 1. SDG Problem Statement  
The rise of non-communicable diseases like diabetes poses a significant threat to global health, particularly in low- and middle-income countries. Early detection can prevent complications, reduce treatment costs, and save lives. This project supports **SDG 3: Good Health and Well-being** by using machine learning to predict whether an individual is likely to develop diabetes based on medical indicators.

---

## 🛠️ 2. Machine Learning Approach  
We applied **supervised learning** using two models:
- **Random Forest Classifier**
- **Logistic Regression**

The models were trained on the **Pima Indians Diabetes Dataset**, which includes features such as glucose level, BMI, age, and blood pressure.

---

## 📊 3. Results Summary

| Model                 | Accuracy | F1-Score (Diabetic Class) |
|----------------------|----------|----------------------------|
| Random Forest         | XX%      | XX                         |
| Logistic Regression   | XX%      | XX                         |

*Random Forest* performed better in both accuracy and F1-score. Feature importance analysis showed **glucose, BMI, and age** were key predictors.

---

## ⚖️ 4. Ethical & Social Considerations  

- **Bias:** The dataset represents a specific demographic, so the model may not generalize across populations. Broader, inclusive datasets are needed.  
- **Fairness:** ML predictions should support but not replace clinical decision-making.  
- **Impact:** This model demonstrates how AI can aid early diagnosis, reducing healthcare burdens and saving lives in resource-limited settings.

---

📁 *Notebook:* [ml-health-ai-sdg3.ipynb](./ml-health-ai-sdg3.ipynb)  
📦 *Dataset:* [Pima Indians Diabetes Database on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
