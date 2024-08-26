# CODETECH-TASK2
NAME : SAMALA LAXMI PRASANNA

COMPANY : CODETECH IT SOLUTIONS

ID: CT08DS6977

DOMAIN : ARTIFICIAL INTELLIGENCE

DURATION : AUGUST TO SEPTEMBER 2024

MENTOR : NEELA SANTHOSH KUMAR

Project Overview: AI Model Evaluation and Comparison Using the Iris Dataset

1. Introduction
Evaluating the performance of AI models is essential to determine their effectiveness in solving specific problems. This project involves implementing, evaluating, and comparing different AI models using the Iris dataset, a classic dataset in machine learning. The goal is to classify Iris species based on various features, such as sepal length, sepal width, petal length, and petal width.

2. Objectives
- Load and Explore Data: Load the Iris dataset and understand its structure.
- Preprocess the Data: Prepare the data by splitting it into training and test sets, and standardizing the features.
- Implement Models: Implement various classification models including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine.
- Evaluate Models: Evaluate the models using metrics like Accuracy, Precision, Recall, and F1 Score.
- Compare Models: Compare the performance of these models and visualize the results to identify the most effective model for the classification task.

3. Dataset Description
The Iris dataset consists of 150 samples from three species of Iris flowers: Iris setosa, Iris versicolor, and Iris virginica. Each sample has four features:
- Sepal Length
-Sepal Width
- Petal Length
- Petal Width

The target variable is the species of the Iris flower, which is a categorical variable with three possible values.

4. Methodology
- Data Loading: The dataset is loaded using the `load_iris` function from Scikit-Learn.
- Data Preprocessing: Features are separated from the target variable, and the dataset is split into training and test sets. The features are standardized to ensure that all models perform optimally.
- Model Implementation: Four different classification models are implemented:
  - Logistic Regression
  -Decision Tree Classifier
  - Random Forest Classifier
    -Support Vector Machine (SVM)
  
- Model Evaluation: Each model is trained on the training set and evaluated on the test set using the following metrics:
  - Accuracy: The proportion of correct predictions.
  - Precision: The ratio of correctly predicted positive observations to the total predicted positives.
  - Recall: The ratio of correctly predicted positive observations to all observations in the actual class.
  - F1 Score: The weighted average of Precision and Recall, useful for imbalanced datasets.

- Visualization: The performance metrics for each model are compared and visualized using bar charts.

5. Results
The project provides a clear comparison of the performance of different models on the Iris dataset. This comparison helps in identifying which model is best suited for this classification task based on the chosen evaluation metrics.

6. Conclusion
The project successfully demonstrates the process of model evaluation and comparison in a machine learning context. The results highlight the strengths and weaknesses of each model, providing insights into model selection for similar classification tasks. This project serves as a foundational exercise for understanding how to evaluate and compare AI models in practical applications.
