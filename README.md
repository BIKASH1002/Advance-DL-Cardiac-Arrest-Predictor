# **A Deep Learnining Framework for Prediction of Cardiopulmonary Arrest**

# **Overview**

This project presents a comparative analysis of various predictive models for forecasting cardiopulmonary arrest (heart stroke) using machine learning and deep learning algorithms. The study specifically focuses on enhancing prediction accuracy by leveraging advanced neural network techniques, including Artificial Neural Networks (ANN), Transfer Learning, Model-Agnostic Meta-Learning (MAML) and Layer-wise Relevance Propagation (LRP). Among the algorithms tested, ANN demonstrated the highest accuracy of 94% using the Cleveland dataset.

# **Problem Statement**

Cardiopulmonary arrest is a significant health concern worldwide. While it traditionally affected older populations, it is now increasingly observed among adolescents. Given the critical need for early diagnosis, this project explores the development of prediction models that can analyze medical datasets and forecast the likelihood of heart strokes with high accuracy.

# **Data Understanding**

Two primary datasets are used for this study:

**1) Cleveland Dataset:** This dataset contains both categorical and numerical attributes with 5110 records, making it a versatile dataset for testing different machine learning models. It includes features like age, gender, cholesterol levels and smoking status, among others.

**2) Framingham Dataset:** This dataset primarily consists of numerical data with 4240 records, focusing on traditional cardiovascular risk factors such as blood pressure, BMI and glucose levels. It also includes stroke risk prediction over 10 years.

These datasets are commonly used in cardiovascular research and contain relevant features that have been validated by previous studies. The inclusion of both numerical and categorical data allows us to test and optimize a wide range of models for the best performance.

# **Methodology**

The project implements multiple deep learning algorithms across two datasets: Cleveland and Framingham. The datasets were preprocessed and various models were trained to determine the most accurate predictive framework. The study also introduces a new attribute called gamma prime fibrinogen, which shows potential in boosting prediction performance.

# **Setup**

Jupyter Notebook (for interactive development)

**Libraries:** numPy, pandas, matplotlib, scikit-learn, keras, tensorFlow

# **Advance Techniques Employed**

**1) Transfer Learning:** Utilized ResNet18, transforming numerical data into a heatmap representation for processing.

**2) Model-Agnostic Meta-Learning (MAML):** Focused on acquiring model parameters that can be fine-tuned for new tasks.

**3) Layer-wise Relevance Propagation (LRP):** Provided insights into the impact of individual features on the model’s output.

# **Workflow**

<p align="center">
    <img src="https://github.com/user-attachments/assets/9eae9f9e-5959-4a38-9c79-0bd07c6cf58a" alt="Flow diagram"/>
</p>

# **Implementation**

1) Data preprocessing, including handling missing values, normalization and feature selection.
2) Splitting the dataset into training and testing subsets.
3) Training and evaluating models using algorithms like Logistic Regression, ANN and Transfer Learning.
4) Comparing the accuracy across different algorithms for both datasets.
5) Identifying the best-performing model based on accuracy and other performance metrics like F1-score.

# **Results**

<div align = "center">
    
| Algorithm                              | Dataset Accuracy (in %) |            |
|----------------------------------------|--------------------------|------------|
|                                        | Cleveland                | Framingham |
| Logistic Regression                    | 93.9                     | 85.4       |
| Long Short-Term Memory                 | 93.9                     | 85.4       |
| Artificial Neural Network (ANN)        | 94.1                     | 85.4       |
| Transfer Learning                      | 93.9                     | 85.4       |
| Model Agnostic Meta Learning (MAML)    | 92.6                     | 85.1       |
| Layer wise Relevance Propagation (LRP) | 92.6                     | 85.5       |

</div>

**GRAPHICAL ANALYSIS**

<table>
    <tr>
        <td>
            <img src="https://github.com/user-attachments/assets/151afecc-30a3-40db-a548-9d2760ee672d" alt="Cross Validation" width="300">
            <p align="center">Cross Validation for Best Model</p>
        </td>
        <td>
            <img src="https://github.com/user-attachments/assets/f95a6bc7-cbd8-49d8-8fbc-685bb2acc9f6" alt="ROC" width="300">
            <p align="center">ROC Curve for Best Model</p>
        </td>
    </tr>
</table>


# **Conclusion**

ANN outperformed other algorithms, achieving a maximum accuracy of 94% on the Cleveland dataset, making it the most suitable model for cardiac arrest prediction.

# **Credits**

**1) Dataset link:** a) https://archive.ics.uci.edu/dataset/45/heart+disease

b) https://biolincc.nhlbi.nih.gov/studies/framcohort/
 
**2) Guide:**
Dr. Sandeep Kumar Satapathy, Professor, Vellore Institute of Technology, Chennai
