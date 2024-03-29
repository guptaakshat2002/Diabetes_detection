# Diabetes_detection
This repository contains an algorithm for detecting diabetes by comparing various machine learning techniques including K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree, and Logistic Regression. The algorithm is designed to analyze input data related to health parameters and predict the likelihood of an individual having diabetes.

There are various parameter require for detecting diabetes, these parameter are as follow:-
     
  1. Gender
  2. Glucose
  3. Age
  4. Blood Pressure
  5. Insulin
  6. BMI(Body mass index)
  7. Pregancies
  8. Skin thickness
     
Requirements
To run the algorithm, you need the following dependencies:

  1. Python 3.x
  2. Numpy
  3. pandas
  4. scikit-learn


You can install the dependencies using pip:

          pip install numpy pandas scikit-learn

Dataset
The algorithm uses a dataset containing various health parameters such as glucose level, blood pressure, insulin level, etc., along with a binary label indicating the presence or absence of diabetes. The dataset should be split into features (X) and labels (y) and to know more about dataset see https://github.com/guptaakshat2002/Diabetes_detection/blob/main/diabetese.csv

Algorithms Implemented: 

  1. K-Nearest Neighbors (KNN): This algorithm classifies a data point based on the majority class of its 'k' nearest neighbors. It is a simple and effective classification algorithm.
  2. Support Vector Machine (SVM): SVM is a powerful algorithm for classification tasks. It finds the hyperplane that best separates the classes in the feature space.
  3. Decision Tree: Decision trees are versatile algorithms used for classification and regression tasks. They partition the feature space into regions and assign a label to each region.
  4. Logistic Regression: Despite its name, logistic regression is a classification algorithm that models the probability of a binary outcome using a logistic function.

Usage:

Clone the repository:
                        
    git clone https://github.com/your_username/diabetes-detection.git
    cd diabetes-detection
  1. Prepare your dataset and ensure it is formatted correctly with features (X) and labels (y).
  2. Update the file paths in the code to point to your dataset.
  3. Run the algorithms individually or compare them by running the main script:

    python main.py

Results: 
The algorithm provides evaluation metrics such as accuracy, precision, recall, and F1-score for each algorithm implemented. It also includes visualizations of performance metrics to aid in comparison of various patient record and this model achieve 80% accuracy which is highest on pima dataset and to see full detail on https://github.com/guptaakshat2002/Diabetes_detection/blob/main/result.txt

Conclusion:
This project demonstrates the effectiveness of various machine learning algorithms in detecting diabetes based on health parameters. The results can be utilized to improve diagnosis and treatment strategies for individuals at risk of diabetes.

Author and Developer:

  1. Akshat Gupta (akshatg989@gmail.com)
  2. Preeti (preeti06moni@gmail.com)

Acknowledgments
Special thanks to kaggle and google for providing the dataset used in this project.
Inspired by [Diabetes detection using deep learning algorithms by Swapna G., Vinayakumar R., Soman K.P.].
For research paper click on https://github.com/guptaakshat2002/Diabetes_detection/blob/main/RESEARCH%20PAPER.pdf
