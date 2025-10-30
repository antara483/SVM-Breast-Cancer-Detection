## 🧬 Breast Cancer Classification using SVM

This project focuses on building a binary classification model to predict whether a breast tumor is Malignant (M) or Benign (B) using the Breast Cancer Dataset from Kaggle.

The model uses Support Vector Machines (SVM) with both Linear and RBF kernels, explores the kernel trick, and performs hyperparameter tuning and cross-validation to achieve high accuracy.

#### 🧰 Tech Stack

Python | Scikit-learn | NumPy | Pandas | Matplotlib

### 🚀 What I Did in This Project
#### 1️. Data Preparation

Loaded the Kaggle breast cancer dataset using Pandas.

Removed unnecessary columns like id and handled missing data.

Encoded the categorical target column (diagnosis) using LabelEncoder.

Scaled all features using StandardScaler for better SVM performance.

Split the dataset into training and testing sets using stratified sampling.

#### 2️. Model Training

Trained two SVM classifiers:

Linear Kernel SVM — finds a straight-line boundary.

RBF Kernel SVM — applies the kernel trick to classify non-linear data.

#### 3. Visualization

Used a 2D synthetic dataset to visualize the decision boundary of SVMs.

Demonstrated how margin maximization and kernel transformations affect boundaries.

#### 4️. Hyperparameter Tuning

Tuned C (Regularization) and gamma (Kernel Coefficient) using GridSearchCV.

Selected the best parameters based on cross-validation scores.

#### 5️. Model Evaluation

Evaluated models using accuracy, confusion matrix, and cross-validation.

Compared Linear vs RBF kernel performance.

Achieved >95% accuracy on test data.

