# 🧬 Breast Cancer Metastases Detection Using Machine Learning

This project focuses on predicting breast cancer metastases using clinical data and machine learning models. It showcases how structured medical data can be used to build predictive models that support early diagnosis and treatment planning.

---

## 📁 Dataset

The dataset contains anonymized patient health records with features relevant to breast cancer diagnosis and metastasis prediction.

### Features:
- Clinical variables such as age, tumor size, lymph node involvement
- Diagnostic metrics such as cell density and biopsy results
- Target label: `metastasis` (0 = No metastasis, 1 = Metastasis)

---

## 🧪 Preprocessing

- **Missing values**: Filled using mean or median imputation
- **Encoding**: 
  - Label encoded categorical features
- **Feature scaling**: Applied `StandardScaler` to normalize numerical data
- **Splitting**: Divided dataset into training and testing sets using an 80/20 split

---

## 🧠 Model

Implemented three machine learning models using `scikit-learn`:

1. **Logistic Regression**  
   - Simple, interpretable linear model

2. **Decision Tree Classifier**  
   - Visual and intuitive model with control over depth and splits

3. **Random Forest Classifier**  
   - Ensemble method with high accuracy and resistance to overfitting

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

Used `classification_report` and `confusion_matrix` for performance evaluation.

---

## 📌 Key Insights

- The Random Forest model outperformed other models in prediction accuracy (~94%).
- Early detection of metastases is strongly linked to specific diagnostic features.
- Feature importance analysis helped interpret key clinical indicators.

---

## ▶️ Usage

```bash
# Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the notebook
jupyter notebook cancer_detection.ipynb
```

---

## 📂 Folder Structure

```
cancer_detection/
├── cancer_detection.ipynb
├── dataset/
│   └── breast_cancer_data.csv
├── models/
│   ├── rf_model.pkl
├── outputs/
│   └── visualizations, reports
└── README.md
```

---

## 📈 Future Improvements

- Incorporate larger, real-world clinical datasets
- Try ensemble boosting methods (XGBoost, LightGBM)
- Improve interpretability with SHAP or LIME
- Extend project with deep learning on histopathology images

---

## 👨‍💻 Author

Deniz Arda YILDIZ  
Email: [your.email@example.com]  
GitHub: [github.com/your-username]  
LinkedIn: [linkedin.com/in/your-profile]

---

## 📝 License

This project is open-source and available under the MIT License.
