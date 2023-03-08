# dog_breed_classifier

### End-To-End Multi-Class Dog Breed Classification

This project builds a multi class image classifier using TensorFlow 2.0 and TensorFlow Hub.

## 1. Problem:
Identifying the breed of a given dog image.

## 2. Data
The data we are using is from Kaggle's dog breed classification competition.

https://www.kaggle.com/c/dog-breed-classification/data

## 3. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/c/dog-breed-identifier/classification/overview/evaluation

## 4. Features
Some information about the data:
* We are dealing with images (unstructured data) so it's probably the best we use deep learning/transfer learning.
* Data contains 120 breeds of gogs (this means there are 120 different classes), therefore multiclass.
* Theer are 10,000+ images in the training set(these images have labels)
* There are 10,000+ images in the test set(these images do not have labels and need to be predicted)
