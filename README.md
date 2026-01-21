Sampling Techniques on Imbalanced Dataset

Objective
To analyze how different sampling techniques affect the performance of machine learning models on an imbalanced dataset.

Dataset
Numerical transaction dataset
Target column: Class
 0 → Normal transaction
 1 → Fraudulent transaction
Dataset is highly imbalanced, making sampling necessary.

Methodology 
1. Load and inspect the dataset.
2. Separate features (X) and target (y).
3. Split data into training and testing sets using stratification.
4. Apply different sampling techniques on training data.
5. Train models and evaluate using accuracy.

Sampling Techniques Used
1. No Sampling: Original imbalanced data (baseline)
2. SMOTE: Over-sampling of minority class
3. Random Under-Sampling: Reduces majority class
4. SMOTE + Tomek: Over-sampling with noise removal

Models Used
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

Result Table
1. Displays model-wise accuracy for each sampling technique.
2. Helps compare the impact of sampling on each classifier.

Result Graph
1. Bar graph comparing accuracy scores.
2. X-axis: Model & sampling method
3. Y-axis: Accuracy
4. Used for quick visual comparison.

Conclusion
Sampling techniques improve model performance on imbalanced data. SMOTE-based methods generally give better and more stable results, especially when combined with ensemble models like Random Forest.
