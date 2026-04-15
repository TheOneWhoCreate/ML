# Support Vector Machine (SVM) Classifier

This project explores the implementation and performance analysis of Support Vector Machines (SVM) using various kernels. The notebook focuses on dataset preprocessing, hyperparameter tuning via Grid Search, and performance evaluation on real-world datasets.

## What's Covered

### Data Understanding & Preprocessing
- Loading real-world datasets (e.g., Wine dataset) using Scikit-learn
- Performing stratified train-test splits (70:30 ratio)
- Feature scaling using MinMaxScaler to normalize data within [0, 1]

### Model Implementation
- Training SVM classifiers with multiple kernel functions: Linear, Polynomial, and RBF
- Implementing baseline models without parameter tuning

### Hyperparameter Tuning
- Applying Grid Search CV with 5-fold cross-validation
- Optimizing parameters:
- Linear: C values
- Polynomial: C values and degree
- RBF: C values and gamma

### Performance Evaluation
- Calculating key metrics: Accuracy, Precision, Recall, and F1-score
- Visualizing results through Confusion Matrices for each kernel
- Plotting Decision Boundaries in 2D space

### What You Will Learn

- How to systematically implement SVM classifiers for multi-class problems.
- How to find optimal model parameters using the Grid Search technique.
- How to interpret the impact of different kernels (Linear vs. Non-linear) on model accuracy.
- How to evaluate and visualize classification performance through confusion matrices.
- How SVM decision boundaries adapt to data based on hyperparameter configurations.