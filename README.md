# Parkinsons disease prediction using Machine Learning

The aim of the project seems to be the prediction or classification of the positive history of Parkinson's disease within families based on various features or attributes related to individuals. The project appears to focus on using machine learning techniques to build predictive models that can identify or classify whether an individual has a positive history of Parkinson's disease.

**Dataset Overview**
The dataset contains information about various features related to Parkinson's disease, such as age, gender, symptoms, and speech-related metrics.
Preprocessing steps included converting categorical variables into numerical representations for machine learning models.

**Data Preparation and Splitting**
After loading the dataset, it was split into features (X) and the target variable (y) for classification.
The dataset was further divided into training and testing sets using train_test_split.

**Model Implementation and Evaluation**
Various classification algorithms were utilized, including Logistic Regression, Random Forest, Gaussian Naive Bayes, SVM, and K-Nearest Neighbors (KNN).
Each model was trained using the training dataset and evaluated based on its performance metrics on the test dataset.
Evaluation metrics such as accuracy, confusion matrices, and classification reports were used to assess model performance.

**Model Performance Summary**
Random Forest achieved a perfect training score of 100% and an impressive test score of 95.83%.
KNN also attained a perfect training score of 100% and matched the Random Forest's test score of 95.83%.
Gaussian Naive Bayes exhibited excellent performance with a 100% training score and a 95.83% test score.
SVM Model scored 100% on the training data but showed slightly lower performance on the test set with a score of 79.17%.
Logistic Regression resulted in a 100% training score but had a lower test score of 75%.

**Conclusion**
The Random Forest, KNN, and Gaussian Naive Bayes models demonstrated robust performance in predicting the positive history of Parkinson's disease in families based on the given features.
These models could be considered for further analysis or implementation in real-world scenarios due to their high accuracy on the test dataset.
