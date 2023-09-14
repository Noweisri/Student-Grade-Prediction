# Student-Grade-Prediction
 In this file, I took a Students' Academic Performance Dataset, and I tried to predict their grades by trying many algorithms that have the best results.
 below are the best classification algorithms for the dataset:
 
  - Logistic regression "with max iterations = 1300" | Accuracy = 0.72
      Logistic regression is a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes).

  - Naïve Bayes | Acuuracy = 0.68
      Naive Bayes is a classification algorithm based on Bayes’ theorem. It is particularly suited when the dimensionality of the inputs is high. It makes an assumption of independence among predictors which  simplifies the computation.

  - K Nearest neighbor "with num of neighbors = 12" | Accuracy = 0.66
        K-nearest neighbors (KNN) is a type of supervised learning algorithm used for both regression and classification. KNN tries to predict the correct class for the test data by calculating the distance between the test data and all the training points. Then select the K number of points which is closest to the test data.

Decisions done to Clean the data :
      1- Any alphabetical attributes were converted to numerical values (either binary values for yes/no or range values 0…x) to work properly with any model.
      2- I removed the "NationalityID" and "PlaceOfBirth" columns since it is a bit difficult to convert them to numerical values.
      3- The dataset is split into two sets, the train set with 80% / 384 and the test set with 20% / 96, with random state = 93.

finally thanks to IBRAHIM ALJARAH for the dataset

Link for the dataset: https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data
