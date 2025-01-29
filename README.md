# 🩺 Diabetes Prediction Model

## 📊 About The Project
This project implements a machine learning model that predicts whether individuals have diabetes based on various health metrics. The model uses an ensemble approach combining Logistic Regression and KNN algorithms for improved prediction accuracy.

## 🎯 Objectives
- Assist in early detection of diabetes
- Generate meaningful predictions from health data
- Compare performance of different machine learning models

## 📝 Dataset Features
Our dataset includes the following features:
- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- Outcome (0: Non-Diabetic, 1: Diabetic)

## 📊 Dataset Information
The dataset used in this project is the Pima Indians Diabetes Database, originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The dataset is included in the repository as `diabetes.csv` and is also available on [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

### Dataset Details:
- Source: Kaggle
- Format: CSV
- Size: 768 instances
- Target Population: Females of Pima Indian heritage, age 21+
- Features: 8 numeric predictive attributes and 1 target variable
- File: `diabetes.csv` (included in repository)

## 🛠️ Technologies Used
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- imbalanced-learn (SMOTE)

## 📈 Model Performance
Our ensemble model (Logistic Regression + KNN) achieved the following results:
- Accuracy: 0.76
- Weighted F1-Score: 0.77
- Precision for Non-Diabetic cases: 0.86
- Precision for Diabetic cases: 0.63

## 🌟 Key Features
- SMOTE technique for handling data imbalance
- Combination of two different algorithms
- Detailed performance metrics
- Visual analysis tools

## 🚀 How to Run
1. Install required libraries:
```python
pip install pandas numpy scikit-learn seaborn matplotlib imbalanced-learn
```
2. Launch Jupyter Notebook
3. Open `main.ipynb`
4. Run all cells sequentially

## 💡 Results
- The ensemble model outperformed both standalone KNN (0.72) and Logistic Regression (0.75)
- Model shows high accuracy in detecting non-diabetic cases
- Room for improvement in detecting diabetic cases

## 🔍 Model Insights
- Successfully handles imbalanced dataset through SMOTE
- Combines strengths of both Logistic Regression and KNN
- Provides reliable predictions for healthcare screening

## 👥 Contributing
We welcome your contributions to improve the project! Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request

## 📫 Contact
For questions and suggestions:
- Open an issue
- Submit a pull request
- Connect through project discussions

## 📄 License
This project is licensed under the MIT License.

---
⭐️ If you found this project helpful, don't forget to give it a star!

## 🔗 Additional Resources
- [Dataset Source](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- [Documentation](./docs)
- [Project Presentation](./Diabetes%20Prediction%20Presentation.pptx)
