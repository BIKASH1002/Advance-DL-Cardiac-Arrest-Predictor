# **Overview**

This project presents a comparative analysis of various predictive models for forecasting cardiopulmonary arrest (heart stroke) using machine learning and deep learning algorithms. The study specifically focuses on enhancing prediction accuracy by leveraging advanced neural network techniques, including Artificial Neural Networks (ANN), Transfer Learning, Model-Agnostic Meta-Learning (MAML) and Layer-wise Relevance Propagation (LRP). Among the algorithms tested, ANN demonstrated the highest accuracy of 94% using the Cleveland dataset.

# **Problem Statement**

Cardiopulmonary arrest is a significant health concern worldwide. While it traditionally affected older populations, it is now increasingly observed among adolescents. Given the critical need for early diagnosis, this project explores the development of prediction models that can analyze medical datasets and forecast the likelihood of heart strokes with high accuracy.

# **Methodology**

The project implements multiple deep learning algorithms across two datasets: Cleveland and Framingham. The datasets were preprocessed and various models were trained to determine the most accurate predictive framework. The study also introduces a new attribute called gamma prime fibrinogen, which shows potential in boosting prediction performance.

# **Datasets Used**

Cleveland Dataset: Contains both categorical and numerical data with 5110 records.

Framingham Dataset: Contains only numerical data with 4240 records.

# **New Techniques Employed**

**1) Transfer Learning:** Utilized ResNet18, transforming numerical data into a heatmap representation for processing.

**2) Model-Agnostic Meta-Learning (MAML):** Focused on acquiring model parameters that can be fine-tuned for new tasks.

**3) Layer-wise Relevance Propagation (LRP):** Provided insights into the impact of individual features on the model’s output.

# **Workflow**

1) Selection of Dataset

2) Data Pre-processing

3) Algorithm Selection

4) Implementation of Algorithm

5) Decision Making

# **Implementation**

1) Data preprocessing, including handling missing values, normalization, and feature selection.
2) Splitting the dataset into training and testing subsets.
3) Training and evaluating models using algorithms like Logistic Regression, ANN, and Transfer Learning.
4) Comparing the accuracy across different algorithms for both datasets.
5) Identifying the best-performing model based on accuracy and other performance metrics like F1-score.

# **Results**

| Algorithm                              | Dataset Accuracy (in %) |            |
|----------------------------------------|--------------------------|------------|
|                                        | Cleveland                | Framingham |
| Logistic Regression                    | 93.9                     | 85.4       |
| Long Short-Term Memory                 | 93.9                     | 85.4       |
| Artificial Neural Network (ANN)        | 94.1                     | 85.4       |
| Transfer Learning                      | 93.9                     | 85.4       |
| Model Agnostic Meta Learning (MAML)    | 92.6                     | 85.1       |
| Layer wise Relevance Propagation (LRP) | 92.6                     | 85.5       |

# **Conclusion**

ANN outperformed other algorithms, achieving a maximum accuracy of 94% on the Cleveland dataset, making it the most suitable model for cardiac arrest prediction.

# **Future Scope**

Introducing new attributes like gamma prime fibrinogen.
Modifying activation functions in neural networks.
Extending the model to other medical conditions such as diabetes and cancer.
