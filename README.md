### Gun and Knife Classification using Multiple Classifiers

### 1. Introduction
This project aims to classify images of various types of firearms (such as rifles, handguns, shotguns, submachine guns, sniper rifles, etc.) and knives using nine different classifiers.

### 2. Classifiers
1. Support Vector Machine (SVM)
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. AdaBoost
7. Logistic Regression
8. Naive Bayes
9. Convolutional Neural Network (CNN)

### 3. Dataset
The dataset consists of labeled images of guns and knives, categorized into nine classes:
1. Automatic Rifle
2. Bazooka
3. Grenade Launcher
4. Handgun
5. Knife
6. Shotgun
7. Submachine Gun (SMG)
8. Sniper Rifle
9. Sword

### 4. Implementation
The project utilizes Python and OpenCV for image preprocessing, feature extraction, and resizing. Each classifier is trained separately using the labeled image dataset. The training process involves resizing the images to a standard size, converting them into arrays, and then feeding them into the respective classifiers.

### 5. Evaluation
The performance of each classifier is evaluated based on metrics such as accuracy, precision, recall, and F1-score. The evaluation results are compared to determine the effectiveness of each classifier in accurately classifying images of guns and knives.

### 6. Dependencies
- Python 3.x
- OpenCV
- NumPy
- Scikit-learn
- TensorFlow/Keras (for CNN)

### 7. Usage
To use the project:
1. Clone the repository.
2. Install the required dependencies.
3. Run the scripts for training and testing each classifier.
4. Evaluate the performance metrics for each classifier.
5. Experiment with different classifiers and parameters for optimization.
