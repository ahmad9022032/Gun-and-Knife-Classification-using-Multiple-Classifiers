Gun and Knife Classification using Multiple Classifiers
This project aims to classify images of various types of firearms (such as rifles, handguns, shotguns, submachine guns, sniper rifles, etc.) and knives using nine different classifiers.

Classifiers
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Gradient Boosting
AdaBoost
Logistic Regression
Naive Bayes
Convolutional Neural Network (CNN)
Dataset
The dataset consists of labeled images of guns and knives, categorized into nine classes:

Automatic Rifle
Bazooka
Grenade Launcher
Handgun
Knife
Shotgun
Submachine Gun (SMG)
Sniper Rifle
Sword
Implementation
The project utilizes Python and OpenCV for image preprocessing, feature extraction, and resizing. Each classifier is trained separately using the labeled image dataset. The training process involves resizing the images to a standard size, converting them into arrays, and then feeding them into the respective classifiers.

Evaluation
The performance of each classifier is evaluated based on metrics such as accuracy, precision, recall, and F1-score. The evaluation results are compared to determine the effectiveness of each classifier in accurately classifying images of guns and knives.

Dependencies
Python 3.x
OpenCV
NumPy
Scikit-learn
TensorFlow/Keras (for CNN)
Usage
To use the project:

Clone the repository.
Install the required dependencies.
Run the scripts for training and testing each classifier.
Evaluate the performance metrics for each classifier.
Experiment with different classifiers and parameters for optimization.
