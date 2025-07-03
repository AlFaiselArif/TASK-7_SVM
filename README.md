# Task 7 - Support Vector Machines (SVM)

# Objective
Use Support Vector Machines for both linear and non-linear (RBF) classification on the Breast Cancer Dataset.

# Tools Used
- Python
- Scikit-learn
- Matplotlib
- NumPy

# What I Did
- Loaded Breast Cancer Dataset from sklearn
- Scaled the data using StandardScaler
- Trained two SVM models: one with linear kernel, another with RBF kernel
- Performed hyperparameter tuning on the RBF kernel using GridSearchCV
- Evaluated model performance using classification report and cross-validation
- Visualized the decision boundary using PCA for 2D projection

# Results
- Linear SVM Accuracy: ~96%
- RBF SVM Accuracy (after tuning): ~98%
- Train SVM with Linear Kernel
   SVC
  SVC(C=1, kernel='linear')
- Train SVM with RBF Kernel
     SVC
  SVC(C=1)
- Visualization of the decision boundary shown using matplotlib
- SVC
  SVC(C=100, gamma=0.001)
  
# Dataset
Used `load_breast_cancer()` from sklearn.

