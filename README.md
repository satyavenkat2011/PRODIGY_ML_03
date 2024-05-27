# PRODIGY_ML_03
HII,
Image Classification Using SVM and KNN


Overview

This project involves implementing a Support Vector Machine (SVM) and a K-Nearest Neighbors (KNN) classifier to classify images of cats and dogs. The task was assigned as part of an internship project by ProdigyInfo Tech. The dataset used for training and testing the models is from Kaggle.

Project Structure

The project is organized as follows:

Data Preparation

Model Training and Evaluation

Prediction on New Images

Data Preparation

The dataset consists of images of cats and dogs which are preprocessed and split into training and testing sets. The images are resized to 128x128 pixels and flattened into vectors for model training.

Model Training and Evaluation

Two models were trained on the dataset:

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

SVM Model

Kernel: Linear

Class Weight: Balanced

Gamma: Scale

Max Iterations: Unlimited

The SVM model achieved an accuracy of 52.50% on the test set.

KNN Model

Number of Neighbors: 5

Number of Jobs: -1 (using all processors)

The KNN model achieved an accuracy of 49.64% on the test set.

Prediction on New Images

The models were tested on four new images (case1.jpg, case2.jpg, case3.jpg, case4.jpg). The predictions made by both models are displayed below:

Test Case 1

Prediction by SVM: Cat

Prediction by KNN: Cat

Test Case 2

Prediction by SVM: Dog

Prediction by KNN: Dog

Test Case 3

Prediction by SVM: Cat

Prediction by KNN: Cat

Test Case 4

Prediction by SVM: Dog

Prediction by KNN: Dog


Conclusion
This internship task assigned by ProdigyInfo Tech was successfully completed. The SVM and KNN models were implemented and evaluated for the classification of cat and dog images, demonstrating the application of machine learning techniques in image classification tasks.
