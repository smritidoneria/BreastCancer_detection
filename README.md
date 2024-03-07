Breast Cancer Detection Project

This project aims to detect breast cancer using machine learning algorithms. It achieves an accuracy of 97% in classifying breast cancer tumors as malignant or benign. The algorithms used for testing include logistic regression, random forest,adaboost and decision tree. Among these, random forest yielded the highest accuracy.


Dataset

The project employs the https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data  dataset, which contains features computed from digitized images of fine needle aspirate (FNA) of breast mass. 

Algorithms

Three machine learning algorithms were utilized for training and testing:

Logistic Regression: A linear regression model used for binary classification tasks.
Random Forest: An ensemble learning method based on decision trees, known for its robustness and high accuracy.
Decision Tree: A decision tree model that recursively splits the dataset based on feature values to make predictions.
Adaboost:A boosting algorithm that combines multiple weak classifiers to form a strong classifier.

Results

The performance of each algorithm was evaluated using cross-validation and the following metrics:

Accuracy
Precision
Recall
F1 Score
Random forest achieved the highest accuracy of 97% on the test set.

Usage

To run the breast cancer detection project:

Clone the repository:

git clone https://github.com/yourusername/breastcancerdetection.git
Install the necessary dependencies:

pip install -r requirements.txt

Run the main script:
python main.py


Future Improvements

Explore other machine learning algorithms and ensemble techniques.
Enhance feature engineering to potentially improve model performance.
Incorporate deep learning approaches for feature extraction and classification.

