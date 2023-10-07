
# Pima Indians Diabetes Prediction

## Overview

This project aims to predict the likelihood of diabetes in individuals based on various health-related features. It utilizes machine learning techniques, specifically a Random Forest Classifier, to make predictions.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Author](#Author)

## Dataset

The project uses the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database) available on Kaggle. The dataset includes the following features:

- Pregnancies
- Glucose level
- Blood Pressure
- Skin Thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- Outcome (1 if diabetes, 0 if not)

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/yourusername/your-project.git
   ```

2. Install the required Python libraries using pip:

   ```
   pip install pandas matplotlib seaborn scikit-learn
   ```

3. Download the dataset from the [Kaggle page](https://www.kaggle.com/uciml/pima-indians-diabetes-database) and save it as `diabetes.csv` in the project directory.

## Usage

1. Run the Jupyter Notebook or Python script provided in the project to perform the following steps:

   - Load and explore the dataset.
   - Split the data into training and testing sets.
   - Train a Random Forest Classifier on the training data.
   - Make predictions on the testing data.
   - Evaluate the model's performance using accuracy, precision, recall, and F1-score.
   - Visualize the confusion matrix, ROC curve, and Precision-Recall curve.

2. Interpret the results to understand the model's ability to predict diabetes based on the given features.

## Results

The project achieves an accuracy of approximately 80.52% in predicting diabetes outcomes. Detailed evaluation metrics, including precision, recall, and F1-score, are provided in the project.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, create a new branch, make your changes, and submit a pull request.

## Author

Hassan Anwar
