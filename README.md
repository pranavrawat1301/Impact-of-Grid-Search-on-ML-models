# Impact of Grid Search on ML models
Optimizing a Support Vector Machine (SVM) using Grid Search on a social network ads dataset. This project enhances model accuracy through systematic hyperparameter tuning. k-Fold Cross Validation ensures robustness, while contour plots visualize training and test set results. Explore and adapt the code for improved classification in your projects.

**Overview:**
This project demonstrates the impact of Grid Search on improving the accuracy of a Support Vector Machine (SVM) model for a binary classification task. The dataset involves social network ads, and the SVM is initially trained with default parameters. Grid Search is then applied to fine-tune hyperparameters, resulting in significant accuracy enhancement.

**Key Steps:**
1. **Initial SVM Training:**
   - The SVM model is trained on the social network ads dataset with default parameters.
   - Confusion matrix and accuracy are calculated to evaluate initial model performance.

2. **k-Fold Cross Validation:**
   - k-Fold Cross Validation is applied to assess the SVM's generalization performance.
   - Mean accuracy and standard deviation are reported to evaluate model consistency.

3. **Grid Search Implementation:**
   - Grid Search is employed to find the optimal hyperparameters for the SVM.
   - A grid of hyperparameter values for C (regularization parameter) and kernel type is explored.

4. **Best Model Training:**
   - The SVM is retrained using the best hyperparameters obtained from Grid Search.
   - Confusion matrix and accuracy are calculated to evaluate the improved model.

**Results:**
- The project highlights the impact of Grid Search in optimizing the SVM model, showcasing improved accuracy and generalization.

**Usage:**
1. Run the initial SVM training to establish baseline performance.
2. Apply k-Fold Cross Validation for assessing model consistency.
3. Implement Grid Search to fine-tune hyperparameters for optimal performance.
4. Retrain the SVM using the best parameters obtained from Grid Search.
5. Visualize results using contour plots for both training and test sets.

**Contributions:**
Contributions and feedback are welcome. Users can experiment with different datasets and adapt the code for their classification tasks.

**Tools and Libraries:**
- Python, NumPy, Pandas, Matplotlib, Scikit-learn

**Acknowledgments:**
Acknowledgments to the Scikit-learn community for providing robust tools for machine learning.
