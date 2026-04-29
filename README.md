# 💳 Explainable Credit Risk Assessment using Machine Learning

## 📌 Overview

This project focuses on building an **Explainable AI-based Credit Risk Assessment System** that balances **predictive accuracy** and **interpretability**.

Traditional models like Logistic Regression are interpretable but lack performance, while advanced models like XGBoost offer high accuracy but act as black boxes.

To solve this, we propose a **Confidence-Aware Hybrid Framework** that dynamically selects models based on prediction certainty.

---

## 🎯 Objectives

* Develop a hybrid model combining **Logistic Regression** and **XGBoost**
* Improve **credit risk prediction accuracy**
* Ensure **interpretability for regulatory compliance**
* Introduce **confidence-based model routing**
* Maintain **fairness in decision-making**

---

## 🧠 Proposed Approach

### 🔹 Hybrid Model

* **XGBoost** → Used for high-confidence predictions
* **Logistic Regression** → Used for low-confidence (interpretable) predictions

### 🔹 Confidence-Based Routing

* If prediction confidence is high → accept XGBoost result
* If prediction confidence is low → switch to Logistic Regression

This ensures:
✔ High accuracy
✔ Interpretability when needed
✔ Efficient computation

---

## 🗂️ Project Structure

```
credit-risk-xai/
│
├── lendingClub.ipynb       # Model training on Lending Club dataset
├── germanCredit.ipynb      # Model training on German Credit dataset
├── README.md               # Project documentation
```

---

## 📊 Datasets Used

* **German Credit Dataset**
* **Lending Club Dataset**

These datasets include financial and demographic features used to predict loan default risk.

---

## ⚙️ Technologies Used

* Python 🐍
* Google Colab
* Scikit-learn
* XGBoost
* Pandas & NumPy
* Matplotlib / Seaborn

---

## 📈 Evaluation Metrics

* ROC-AUC
* Precision & Recall
* Accuracy
* Interpretability Coverage
* Fairness Metrics

---

## 🚀 Key Features

* Hybrid ML framework
* Dynamic model selection
* Explainable predictions
* Scalable architecture
* Fairness-aware evaluation

---

## 🔍 Results

* Improved prediction performance compared to traditional models
* Balanced trade-off between **accuracy and interpretability**
* Reduced unnecessary computation using selective explainability

---

## 🤝 Future Improvements

* Real-time deployment using web frameworks
* Integration with financial APIs
* Advanced fairness optimization
* UI dashboard for explainability visualization

---

## 📌 How to Run

1. Open notebooks in **Google Colab**
2. Upload dataset files
3. Run all cells sequentially

---

## 👨‍💻 Author

**Pavitra Sharma**
B.E. Computer Science (AI & ML)
Chandigarh University

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
