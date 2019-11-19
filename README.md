# BreastCancerPrediction-SVM

Breast cancer, the most common cancer among women worldwide accounting for 25% of all cancer cases and effected 2.1 million people in 2015. Early diagnosis significantly increases the chances of survival. 

The key challenge in cancer detection is how to classify tumors into malignant and benign. Machine learning techniques can dramatically improve the accuracy of diagnosis. Research indicates that most experienced physicians can diagnose cancer with 79% accuracy while 91% correct diagnosis can be achieved using Machine Learning techniques.

In this case study, I tried to classify tumors into malignant and benign tumors using features obtained from several cell images. I built a Machine Learning model that is trained using the training data and learns which tumor is malignant and which is benign. After training the model, it uses the testing data to classify the tumors and calculated the accuracy of the model which is .

# Data:
The data used to build the model contains 30 features like radius, texture, perimeter, smoothness and area, symmetry, fractal dimension, concavity, compactness, etc. 
Number of instances (or rows) : 569

Class distribution: 212 Malignant and 357 Benign
Target Class: Malignant or Benign

We can also import the data from sklearn using the command:
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()


I tried to build a Support Vector Machine as a Machine Learning model. The objective of this model is to classify the tumors into Benign and Malignant based on the input data/features provided to the model. 
