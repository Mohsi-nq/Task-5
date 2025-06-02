# Task-5
# Decision Trees and Random Forests - Heart Disease Prediction

This task focuses on using **Decision Tree** and **Random Forest** classifiers to predict the presence of heart disease using the `heart.csv` dataset. The goal is to analyze the model performance, understand overfitting, explore feature importance, and evaluate the models using cross-validation.

---

## Dataset

- **Source**: `/kaggle/input/heart-disease-dataset/heart.csv`
- **Target Column**: `target`
  - `1` = Heart disease present
  - `0` = No heart disease

---

## Steps Performed

### 1. Train a Decision Tree Classifier and Visualize the Tree
- Used `DecisionTreeClassifier` from `sklearn.tree`.
- Fitted the model and visualized the structure using `plot_tree()`.

### 2. Analyze Overfitting and Control Tree Depth
- Compared training vs testing accuracy to observe overfitting.
- Tuned hyperparameter `max_depth` to balance bias-variance.

### 3. Train a Random Forest and Compare Accuracy
- Used `RandomForestClassifier` from `sklearn.ensemble`.
- Compared its accuracy with Decision Tree on the test set.

### 4. Interpret Feature Importances
- Extracted feature importances from the trained Random Forest.
- Plotted the most influential features in predicting heart disease.

### 5. Evaluate Using Cross-Validation
- Applied 5-fold cross-validation using `cross_val_score` from `sklearn.model_selection` to ensure stable accuracy.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

