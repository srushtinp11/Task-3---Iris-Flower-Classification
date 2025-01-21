# Task-3---Iris-Flower-Classification

## Project Overview

This project demonstrates the use of a **Random Forest Classifier** to classify the famous Iris dataset into its three species: *Setosa*, *Versicolor*, and *Virginica*. The implementation includes data preprocessing, model training, evaluation, and visualization of the results.

---

## Project Description

The project involves:
- Loading the Iris dataset.
- Data preprocessing (encoding, scaling, splitting into train/test sets).
- Training a **Random Forest Classifier** to predict the species of iris flowers based on four features: `sepal_length`, `sepal_width`, `petal_length`, and `petal_width`.
- Evaluating the model's performance using metrics like accuracy, classification report, and confusion matrix.
- Visualizing feature importance, pair plots, and the confusion matrix.

---

## Dataset

- **Source**: The Iris dataset is a classic dataset available in machine learning libraries or can be downloaded.
- **Structure**:
  - **Features**: `sepal_length`, `sepal_width`, `petal_length`, `petal_width`.
  - **Target**: `species` (three classes: *Setosa*, *Versicolor*, *Virginica*).

---

## Dependencies

Install the required libraries before running the code:

```bash
pip install pandas scikit-learn seaborn matplotlib
```

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/iris-classification.git
   cd iris-classification
   ```

2. Place the `IRIS.csv` dataset in the root directory.

3. Run the script:
   ```bash
   python iris_classification.py
   ```

---

## Output

- **Model Accuracy**: Displays the accuracy of the classifier on the test dataset.
- **Classification Report**: Precision, Recall, and F1-Score for each class.
- **Confusion Matrix**: Tabular view of predictions vs. actual labels.

---

## Visualizations

1. **Confusion Matrix**: Heatmap showing true vs. predicted labels.
2. **Pair Plot**: Scatter plots of features colored by species.
3. **Feature Importance Plot**: Bar chart showing the importance of each feature as determined by the Random Forest model.

