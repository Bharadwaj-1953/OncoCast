<h1 align="center">
Machine Learning-Based Malignant and Benign <br> Tumor Classification System
</h1>

---

## 📝 Abstract

<div align="justify">

OncoCast focuses on classifying breast tumors as malignant or benign using supervised machine learning and artificial neural network (ANN) models. Utilizing the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, the study analyzes 30 features extracted from digitized biopsy images. Through comprehensive data preprocessing, feature scaling, and model training, both traditional ML classifiers and a custom-built neural network are evaluated.

The objective is to support early diagnosis by maximizing prediction accuracy while minimizing false negatives, which are critical in life-threatening conditions like cancer. OncoCast aims to provide an intelligent diagnostic assistance tool using interpretable, efficient, and replicable machine learning solutions.

</div>

---

## 📁 Repository Structure

```bash
OncoCast/
├── Dataset/
│   └── WDBC.csv                    # Breast cancer dataset (WDBC)
├── OncoCast_ANN_Classifier.ipynb  # ANN model implementation
├── Model_Comparison.ipynb          # Classical ML models and evaluation
├── README.md                       # Project documentation
```

---

## 🎯 Key Features

- 📊 Exploratory Data Analysis (EDA) on WDBC dataset
- 🧹 Data preprocessing and normalization
- 🔍 Implementation of classical ML models (SVM, Random Forest, KNN, etc.)
- 🧠 ANN model using TensorFlow/Keras
- 📈 Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- 📊 Performance comparison with visual plots

---

## 🛠️ Technologies Used

- **Programming Language**: Python 3.x
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - TensorFlow
  - Keras
- **Environment**: Jupyter Notebook

---

## 📊 Dataset Description

The **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset comprises 569 instances with 30 numerical features per tumor cell nucleus.

Each instance is labeled as:
- `M`: **Malignant** (Cancerous)
- `B`: **Benign** (Non-cancerous)

**Features include**:
- Radius, Texture, Perimeter, Area, Smoothness, Concavity, Symmetry, etc.

More details: [UCI WDBC Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

---

## 📈 Results Summary

| Model                         | Accuracy | Precision | Recall    | F1-Score  |
|------------------------------|----------|-----------|-----------|-----------|
| Support Vector Machine (SVM) | ~97%     | High      | High      | High      |
| Random Forest                | ~96%     | High      | High      | High      |
| K-Nearest Neighbors (KNN)    | ~95%     | High      | High      | High      |
| Artificial Neural Network    | ~98%     | Very High | Very High | Very High |

> 📌 *Detailed performance metrics, confusion matrices, and ROC curves are available in the respective notebooks.*

---

## 📬 Contact Information

For any detailed information, clarification, or collaboration inquiries regarding this project, feel free to reach out:

- **Email**: [manne.bharadwaj.1953@gmail.com](mailto:manne.bharadwaj.1953@gmail.com)
- **LinkedIn**: [Bharadwaj Manne](https://www.linkedin.com/in/bharadwaj-manne-711476249/)

---
