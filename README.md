# Heart Disease Prediction using Decision Tree and Random Forest

This project applies tree-based machine learning models — Decision Tree and Random Forest — to the Heart Disease dataset to predict the presence of heart disease in patients. It includes model training, evaluation, visualization, and feature importance analysis.

## 📁 Dataset

- Source: [Kaggle Heart Disease UCI Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- Contains 14 commonly used attributes such as:
  - `age`, `sex`, `cp` (chest pain type)
  - `trestbps` (resting blood pressure)
  - `chol` (serum cholesterol)
  - `thalach` (max heart rate achieved)
  - `target` (0 = no disease, 1 = disease)

## 🧠 Models Used

- ✅ Decision Tree Classifier
  - Visualization using `Graphviz`
  - Depth-pruning to prevent overfitting
- ✅ Random Forest Classifier
  - Feature importance analysis
  - Improved generalization and accuracy

## 📊 Evaluation Metrics

- Accuracy on test data
- Cross-validation accuracy (CV)
- Feature importance bar chart
- Optional: Classification report and confusion matrix

## 🔧 Tools & Libraries

- Python (Colab / Jupyter Notebook)
- `scikit-learn`, `pandas`, `matplotlib`, `seaborn`
- `graphviz` for tree visualization

## 📈 Results

- Decision Tree Accuracy: ~0.8341463414634147 , approx 83.4%
- Random Forest Accuracy: ~0.9970731707317073 , approx 99.7%
- Cross-validation confirms Random Forest outperforms a plain Decision Tree.
- Top contributing features: `cp`, `thalach`, `ca`, `thal`





