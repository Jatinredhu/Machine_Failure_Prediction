# Machine_Failure_Prediction

This project predicts machine failures using sensor and operational data.  
It leverages machine learning models (Logistic Regression and Random Forest) to classify whether a machine is likely to fail.

---

## 📂 Files in this repository
- `mfp.ipynb` : Jupyter Notebook with full code (data preprocessing, model building, evaluation, visualization).
- `machine_failure.csv` : Dataset used for training and testing.

---

## 🚀 Project Overview
- **Objective:** Predict if a machine will fail based on operational data (temperature, rotational speed, torque, etc.).
- **Algorithms Used:** 
  - Logistic Regression
  - Random Forest Classifier
- **Performance:** 
  - Random Forest achieved ~98% accuracy on the test set.
  - Logistic Regression achieved ~97%.

---

## ⚙️ How to run
1. Clone this repo:
2. git clone https://github.com/Jatinredhu/Machine_Failure_Prediction.git
3. Open `mfp.ipynb` in Jupyter Notebook.
4. Ensure you have required libraries installed.
5. pip install pandas numpy matplotlib seaborn scikit-learn
6. Run the notebook cells sequentially.

---

## 🔍 Results
- High classification accuracy for predicting machine failures.
- Visualizations include heatmaps of feature correlations and confusion matrices for model comparison.

---

## 💡 Future Scope
- Use more advanced models like XGBoost or deep learning.
- Incorporate real-time streaming data for prediction.
- Deploy as a web app or dashboard.

---

## 📚 References
- [Kaggle Machine Failure Dataset](https://www.kaggle.com/datasets/shashanknecrothapa/machine-failure-predictions)
- scikit-learn documentation: https://scikit-learn.org
- Matplotlib: https://matplotlib.org
- Seaborn: https://seaborn.pydata.org

Visualizations:

<img width="553" height="606" alt="Screenshot 2025-07-11 174309" src="https://github.com/user-attachments/assets/0dd636e4-9f82-48e7-9e20-790ef41c3a66" />
<img width="523" height="561" alt="Screenshot 2025-07-11 174250" src="https://github.com/user-attachments/assets/f70fbdab-ecbb-41ed-b7bf-f42b56dc6b10" />
<img width="844" height="487" alt="Screenshot 2025-07-11 174220" src="https://github.com/user-attachments/assets/877275da-da96-47bf-aec0-8257a2792d7c" />
