###### Breast-Cancer-Data-Analytics-Using-R

#### Project Overview
This project focuses on the development of a machine learning algorithm aimed at predicting whether a breast cancer cell is benign or malignant. The dataset utilized for this project is the Breast Cancer Wisconsin (Diagnostic) DataSet, a well-known dataset in the field of medical diagnostics and machine learning.

![flow diagram](https://github.com/user-attachments/assets/7dbb9c6f-98ca-4722-8059-f377111010b1)

#### Objective
The primary objective of this project is to create an accurate and reliable predictive model that can assist medical professionals in the early detection and diagnosis of breast cancer. By distinguishing between benign and malignant cells, the algorithm can potentially improve the prognosis and treatment plans for patients.

#### Dataset
Breast Cancer (Diagnostic) DataSet
The dataset contains 569 instances of breast cancer cases, each with 30 features derived from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe the characteristics of the cell nuclei present in the image and include:

Radius (mean of distances from center to points on the perimeter)
Texture (standard deviation of gray-scale values)
Perimeter
Area
Smoothness (local variation in radius lengths)
Compactness (perimeter^2 / area - 1.0)
Concavity (severity of concave portions of the contour)
Concave points (number of concave portions of the contour)
Symmetry
Fractal dimension ("coastline approximation" - 1)
The target variable in the dataset is a binary classification indicating whether the cells are benign (B) or malignant (M).

#### Methodology
1. Data Preprocessing:

Handling missing values
Normalizing feature values
Splitting the data into training and testing sets

2. Exploratory Data Analysis (EDA):

Visualizing the distribution of features
Analyzing the correlation between features
Understanding the class distribution

3. Model Selection:

Evaluating multiple machine learning algorithms including Logistic Regression, Decision Trees, Random Forest, Support Vector Machines (SVM), and k-Nearest Neighbors (k-NN)
Selecting the best performing model based on accuracy, precision, recall, and F1-score

4. Model Training and Validation:

Training the selected model on the training dataset
Validating the model on the testing dataset
Fine-tuning the model parameters to optimize performance

5. Model Evaluation:

Assessing the model's performance using confusion matrix, ROC-AUC curve, and other relevant metrics
Comparing the results with baseline models to ensure significant improvement

#### Results
The final model demonstrated a high level of accuracy in predicting the nature of breast cancer cells. Detailed performance metrics and visualizations of the model's performance are included in the project.

#### Conclusion
The developed machine learning algorithm provides a robust tool for predicting the benign or malignant nature of breast cancer cells based on the features extracted from digitized images. This tool can potentially assist in early diagnosis and improve treatment outcomes for patients.

#### Future Work
Implementing deep learning techniques for improved accuracy
Expanding the dataset to include more diverse samples
Collaborating with medical professionals to validate and refine the model in clinical settings


#### Visualization and Analytics of Breast Cancer Dataset:

![Graph1](https://github.com/user-attachments/assets/81f72d7d-9fb9-4e0a-8e17-051bfc735186)
![Graph2](https://github.com/user-attachments/assets/b6e41a8d-4273-4665-afdd-927825a97a9f)
![Graph3](https://github.com/user-attachments/assets/052caa30-0a48-44a6-9b5f-7398350b0c3c)
![Graph4](https://github.com/user-attachments/assets/50bd36fb-f20f-45f7-80f2-6a10a9849f2a)

