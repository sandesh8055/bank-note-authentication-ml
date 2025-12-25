# Bank Note Authentication using Machine Learning

This project focuses on classifying banknotes as **genuine** or **forged** using machine learning algorithms.  
Statistical features extracted from wavelet-transformed images are used to train and evaluate classification models.

---

## 📊 Dataset Information

The dataset contains numerical features derived from banknote images:

- **variance**
- **skewness**
- **curtosis**
- **entropy**
- **class** (Target variable: 0 = Genuine, 1 = Forged)

📁 Dataset is stored in the `Data/` directory.

---

## ⚙️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Methodology

1. Loaded and explored the dataset
2. Separated features and target variable
3. Performed train-test split
4. Applied feature scaling using `StandardScaler`
5. Trained the following models:
   - Decision Tree Classifier
   - Random Forest Classifier
6. Evaluated model performance using:
   - Confusion Matrix
   - Accuracy Score

---

## 🚀 Machine Learning Models

### 🔹 Decision Tree Classifier
- Simple and interpretable model
- Achieved high accuracy on test data

### 🔹 Random Forest Classifier
- Ensemble learning approach
- Provided better generalization and higher accuracy compared to Decision Tree

---

## 📈 Results

| Model | Accuracy |
|------|----------|
| Decision Tree | ~97% |
| Random Forest | ~99% |

Random Forest performed better with fewer misclassifications.

---

## 📂 Project Structure

bank-note-authentication-ml/
│
├── Data/
│ └── BankNote_Authentication.csv
│
├── Notenook/
  └──Bank_note_authentication_using_DT&RF.ipynb
│
└── README.md

---

## ✅ Conclusion

This project demonstrates the effective use of machine learning techniques for binary classification problems.  
Random Forest proved to be more robust and accurate due to its ensemble nature.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Model deployment using Flask or FastAPI
- Visualization of decision boundaries
- Cross-validation

---

## 👤 Author

**Sandesh Duduskar**  
GitHub: https://github.com/sandesh8055
