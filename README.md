# -KNN-Handwritten-Digit-Classification
📂 Dataset

Source: sklearn.datasets.load_digits()

Description: Handwritten digit images (0–9) represented as 8×8 pixel grids.

🎯 Objective

To build and evaluate a K-Nearest Neighbors (KNN) classifier for digit recognition and analyze how different values of K affect model performance.

🛠️ Steps Performed

Loaded the Digits dataset and verified feature and target shapes.

Visualized sample digit images with their labels.

Split the dataset into training and testing sets.

Applied StandardScaler for feature normalization.

Trained a KNN model with K = 3 and evaluated accuracy.

Tested multiple K values (3, 5, 7, 9).

Plotted Accuracy vs K to identify the best K.

Generated a Confusion Matrix to analyze misclassifications.

Displayed test images with predicted labels for final validation.

✅ Conclusion

The notebook demonstrates how KNN performance varies with different K values and provides visual insights into prediction accuracy and classification errors.
