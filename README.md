# Data Science Project: Material Evaluation and Cold Forming  

This repository contains the implementation of a data science project focused on two primary tasks: **Material Evaluation** and **Cold Forming**. The project involves supervised learning approaches for classification tasks and showcases end-to-end data processing, model training, and evaluation using Python in a Jupyter Notebook environment.

## Project Overview  

The primary goal was to classify data points into predefined categories using machine learning models. The dataset used for the project was preprocessed and analyzed with inspiration from course lectures and exercises. The methods applied ensured robust and interpretable results.

### Key Features:  
- Data preprocessing using `pandas` for efficient data manipulation.  
- Data scaling with `StandardScaler` from `sklearn` to ensure consistent feature scaling.  
- Training of supervised learning models:  
  - **K-Nearest Neighbors (KNN)** with `n_neighbors=3`, chosen for its simplicity and visual interpretability.  
  - **Support Vector Machine (SVM)** with a linear kernel (`C=1, random_state=42`), selected for its effectiveness in classifying data separable by hyperplanes.  
- Clear clustering and class separation observed, indicating the effectiveness of the selected models.  

## Workflow  

1. **Data Preparation**:  
   - Data was loaded and processed into structured DataFrames using `pandas`.  
   - Training and testing datasets were created through splitting.  

2. **Scaling**:  
   - Features were standardized using `StandardScaler` to ensure consistent scaling across variables.  

3. **Model Training**:  
   - KNN was chosen for its simplicity and the visual clarity of clusters.  
   - SVM was selected for its robustness in classifying linearly separable data.  
   - Both models achieved **100% accuracy**, eliminating the need for further hyperparameter optimization.  

4. **Evaluation**:  
   - Models were validated on the test dataset, demonstrating excellent performance.  