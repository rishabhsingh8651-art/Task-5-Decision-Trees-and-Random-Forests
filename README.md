# Task 5: Decision Trees and Random Forests

## Project Overview

This project was completed as part of my internship to understand and implement tree-based machine learning algorithms using Python and Scikit-learn.

The project uses a heart disease dataset to train, evaluate, and compare a Decision Tree classifier and a Random Forest classifier.

## Objectives

* Train a Decision Tree classifier and visualize its structure.
* Understand overfitting and control tree depth.
* Train a Random Forest classifier and compare model performance.
* Analyze feature importance.
* Evaluate models using cross-validation.
* Compare classification metrics and confusion matrices.

## Dataset

* **File:** `DATA/heart.csv`
* **Type:** Heart disease dataset
* **Task:** Classification

The dataset is included in the `DATA` folder. The target column represents the class the model is trained to predict. Check the notebook for the exact target-column selection and preprocessing steps.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## Machine Learning Algorithms

### 1. Decision Tree Classifier

A Decision Tree predicts a class by learning decision rules from input features. Its depth is analyzed to understand the effects of underfitting and overfitting.

### 2. Random Forest Classifier

A Random Forest combines multiple decision trees to produce predictions. Its performance is compared with the single Decision Tree.

## Project Workflow

1. Import required Python libraries.
2. Load and explore the dataset.
3. Prepare features and the target variable.
4. Split the data into training and testing sets.
5. Train and visualize the Decision Tree.
6. Analyze overfitting by varying maximum tree depth.
7. Train and evaluate the Random Forest.
8. Compare accuracy and classification reports.
9. Visualize confusion matrices.
10. Analyze feature importance.
11. Evaluate both algorithms using cross-validation.

## Results

The notebook calculates training accuracy, test accuracy, classification reports, confusion matrices, feature importance, and cross-validation scores.

Refer to the notebook outputs for the actual experimental results.

## How to Run

1. Clone or download this repository.
2. Open `Task_5_Decision_Trees_and_Random_Forests.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure the dataset is available at the expected path or upload `heart.csv` when prompted.
4. Run the notebook cells in order.

Install the required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**Note:** The notebook includes a Google Colab file-upload helper. If running locally, you may need to replace the `google.colab` upload code with a local file path.

## Key Learnings

* Decision Tree classification and tree visualization
* Overfitting and model complexity
* Ensemble learning with Random Forests
* Feature importance interpretation
* Model evaluation and cross-validation

## Disclaimer

This project is for educational and internship purposes only. Model predictions from this dataset should not be used for medical diagnosis or clinical decision-making.
