# Handling Imbalanced Dataset using Undersampling

This project demonstrates how to handle **imbalanced classification datasets** using **undersampling techniques** to improve model fairness and performance.

## 📌 Objective
To explore the effects of class imbalance and apply **undersampling** to balance the dataset for better model training.

## ⚙️ Techniques Used
- Exploratory Data Analysis (EDA)
- Class distribution visualization using `seaborn`
- Undersampling using `RandomUnderSampler` from `imblearn`
- Model training using `LogisticRegression`
- Evaluation: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 📂 Files
- `imbalanced_undersampling.ipynb`: Main notebook with code and results
- `Social_Network_Ads.csv`: dataset used

## 📊 Results
Before undersampling:
- Class 0: 257 samples
- Class 1: 143 samples

After undersampling:
- Balanced both classes to 143 samples each

Model showed improved performance metrics across minority class predictions after applying undersampling.

## 🛠 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `imblearn`

---

**📌 Don't forget to star ⭐ the repository if you found it helpful!**
