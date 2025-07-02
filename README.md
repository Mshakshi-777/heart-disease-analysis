# Heart Disease Prediction 🫀

This project uses machine learning to predict the presence of heart disease in patients based on clinical data. It includes thorough data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📁 Files in This Repository

- `Heart_Disease_prediction.ipynb`: The complete notebook containing preprocessing, EDA, model training, and evaluation.
- `README.md`: Project documentation
- `.gitignore`, `LICENSE`: Git and license settings

---

## 📊 Dataset

The dataset contains patient health information such as:
- Age, Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Max Heart Rate (thalach)
- Exercise Induced Angina (exang)
- ST Depression (oldpeak)
- And more...

Target column: `target` (1 = heart disease, 0 = no heart disease)

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Checked for duplicates
   - Converted categorical variables
2. **Exploratory Data Analysis (EDA)**
   - Distribution plots (e.g., age, cholesterol)
   - Correlation heatmap
   - Heart disease frequency across features
3. **Model Building**
   - Trained multiple models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Random Forest
   - Used `train_test_split` and evaluated accuracy
4. **Model Evaluation**
   - Printed accuracy scores
   - Chose the best-performing model based on test accuracy

---

## ✅ Results

- **Best Performing Model**: Logistic Regression
- **Test Accuracy**: ~86.88%

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Mshakshi-777/heart-disease-analysis.git

-----
🙋‍♀️ Author
Shakshi
If you'd like to connect or collaborate, feel free to reach out via LinkedIn.

📌 Acknowledgements
Dataset inspired by the UCI Heart Disease dataset

Thanks to Scikit-learn and open-source community




