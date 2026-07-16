# vortextech-aiml-week2

# Build a Classification Model - AI & ML Internship Track (Week 2)

## Project Overview

This project was completed as part of the **Vortex Tech AI & ML Internship – Week 2** assignment. The objective is to build a machine learning classification model that predicts passenger survival using the Titanic dataset.

The project includes data preprocessing, model training, prediction, and performance evaluation using multiple classification metrics.

---

## Dataset

- Dataset: Titanic Dataset
- Target Variable: **Survived**
  - 0 = Did Not Survive
  - 1 = Survived

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

## Machine Learning Workflow

1. Load the cleaned dataset.
2. Select feature columns and target variable.
3. Encode categorical features.
4. Split the dataset into training and testing sets (80/20).
5. Train a Logistic Regression classification model.
6. Predict survival on the test dataset.
7. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score

---

## Model Used

- Logistic Regression

---

## Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

These metrics help measure the classification performance and prediction quality of the model.

---

## Project Structure

```
vortextech-aiml-week2/
│
├── Build_Classification_Model.ipynb
├── README.md
└── Titanic-Dataset.csv
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/vortextech-aiml-week2.git
```

2. Install the required libraries.

```bash
pip install pandas numpy scikit-learn jupyter
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all notebook cells to train and evaluate the classification model.

---

## Conclusion

The Logistic Regression model successfully predicts passenger survival using the Titanic dataset. The model achieved good classification performance based on Accuracy, Precision, Recall, and F1 Score. Future improvements may include feature engineering, hyperparameter tuning, and testing more advanced machine learning algorithms.

---

## Author

**Muhammad Zeeshan Akhtar**

AI & ML Internship Track – Vortex Tech
