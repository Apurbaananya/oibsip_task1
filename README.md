# Iris Flower Classification
#### Oasis Infobyte Internship Project
![51518iris img1](https://github.com/Apurbaananya/oibsip_task1/assets/142817867/2c776de7-6542-4471-891d-819d71b07f2e)

## Problem Statement:
The iris flower, scientifically called Iris, belongs to a unique genus of flowering plants. This genus includes three main species: Iris setosa, Iris versicolor, and Iris virginica. These species differ in physical characteristics, especially in sepal length, sepal width, petal length, and petal width.

Objective:
The objective of this project is to create a machine learning model that learns from iris flower measurements and accurately classifies them into their respective species. The primary aim is to automate the classification process based on the unique characteristics of each iris species.

Project Details:
- Iris Species: The dataset includes iris flowers from three species: setosa, versicolor, and virginica.
- Key Measurements: The main characteristics for classification are sepal length, sepal width, petal length, and petal width.
- Machine Learning Model: The project involves developing and training a machine learning model to accurately classify iris flowers based on these measurements.

This project is significant as it can streamline and automate the classification of iris species, with potential applications in botany, horticulture, and environmental monitoring.

## Project summary
**Project Description:**

The Iris Flower Classification project aims to develop a machine learning model to classify iris flowers into their respective species based on specific measurements. The three iris species—setosa, versicolor, and virginica—each exhibit distinct characteristics in terms of their measurements.

**Objective:**

The primary goal of this project is to utilize machine learning techniques to build a classification model that accurately identifies the species of iris flowers based on their measurements. The model aims to automate the classification process, providing a practical solution for identifying iris species.

**Key Project Details:**

- **Iris Species:** The dataset includes three species of iris flowers: setosa, versicolor, and virginica.
- **Distinguishing Measurements:** These species can be distinguished by measurements such as sepal length, sepal width, petal length, and petal width.
- **Model Training:** The project involves training a machine learning model on a dataset containing iris flower measurements and their respective species.
- **Classification Goal:** The trained model will classify iris flowers into one of the three species based on their measurements.


## Results
Evaluation Metric:

Recall has been chosen as the primary evaluation metric for the Iris Flower Classification model. After removing overfitted models (those with 100% recall, precision, and F1 scores on the training set), the final list of models is as follows:
| Sl no.  | Classification Model | Accuracy Train  | Accuracy Test |                                  
| ------- | -------------------- | --------------- | ------------- |
|    1    | Decision Tree        |1                | 0.977778      |
|    2    | Random Forest        |1                | 0.977778      |
|    3    | XGB                  |1                | 0.977778      |

## Conclusion
In the Iris flower classification project, the Random Forest model has been selected as the final prediction model for classifying Iris flowers into three species: Iris-Setosa, Iris-Versicolor, and Iris-Virginica. Here are the key conclusions from the project:

- **Data Exploration:** Detailed exploration of the dataset provided insights into feature characteristics and distributions. Notably, Iris-Setosa exhibited distinct features compared to the other two species.
  
- **Data Preprocessing:** Steps included handling missing values and encoding categorical variables to prepare the dataset for modeling.

- **Model Selection:** After evaluating various machine learning models, the Random Forest was chosen for its simplicity, interpretability, and effective performance in Iris species classification.

- **Model Training and Evaluation:** The Random Forest model (tuned) was trained on the dataset and evaluated using appropriate metrics, demonstrating satisfactory accuracy and precision in species classification.

- **Challenges and Future Work:** Challenges included feature engineering and model fine-tuning. Future work may involve exploring advanced techniques to enhance classification accuracy further.

- **Practical Application:** The model can automate Iris species identification in fields like botany and horticulture based on physical characteristics.

In conclusion, the Iris flower classification project successfully utilized the tuned Random Forest model to classify Iris species effectively. It offers practical insights into species differentiation and sets a foundation for future improvements in accuracy and application versatility.


