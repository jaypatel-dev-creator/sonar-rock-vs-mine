#  Sonar Rock vs Mine Classification

##  Project Overview
This project focuses on building a binary classification model to predict whether an object detected by sonar signals is a **Rock (R)** or a **Mine (M)**.

The model is built using **Logistic Regression**, a simple yet effective algorithm for binary classification problems.

---

## 📊 Dataset Information

**Source:** Kaggle – Sonar Dataset  
**Dataset Link:** https://www.kaggle.com/datasets/mayurdalvi/sonar-mine-dataset  

**Samples:** 208  
**Features:** 60 continuous numerical features  

**Target Classes:**
- `R` → Rock  
- `M` → Mine  

The dataset is approximately balanced, so no class imbalance techniques were required.

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Google Colab  

---

## 🔁 Model Workflow

1. Load dataset using Kaggle API  
2. Perform data inspection and preprocessing  
3. Split dataset into training and testing sets  
4. Train Logistic Regression model  
5. Evaluate model performance  
6. Predict class for new unseen input  

---

## Model Evaluation

Since the dataset is balanced, **accuracy** was used as the evaluation metric.

### Training & Testing Accuracy
- **Training Accuracy:** 83.74%  
- **Testing Accuracy:** 78.57%  

The close gap between training and testing accuracy indicates good generalization and low overfitting.

---

##  Model Accuracy Visualization

![Model Accuracy](images/accuracy.png)

---

##  Key Learning Outcomes

- End-to-end ML workflow implementation  
- Understanding binary classification problems  
- Practical use of Logistic Regression  
- Model evaluation and interpretation  

---

##  Future Improvements

- Try advanced models (SVM, Random Forest)
- Add cross-validation
- Deploy model using Streamlit

---


