# DECISION_TREE_IMPLEMENTATION_1

**COMPANY** : CODTECH IT SOLUTION

**NAME** : ROHIT SONEL

**INTERN ID** : CT4MHBA

**BOMAIN** : MACHINE LEARNING

**BATCH DURATION** : DECEMBER 30TH,2024 TO APRIL 30TH,2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

#DESCRIPTION OF TASK 

This project focuses on predicting the likelihood of a student being admitted to a graduate program based on various academic and test performance metrics using a Decision Tree Classifier. The model is developed using a real-world dataset named Admission_Predict.csv, which includes details such as GRE Score, TOEFL Score, University Rating, Statement of Purpose (SOP), Letter of Recommendation (LOR), CGPA, Research experience, and the final "Chance of Admit" value.
The first step involves reading and cleaning the dataset using the pandas library. The column "Chance of Admit" is binarized using a threshold of 0.75, such that the classification model predicts whether a student has a high chance (1) or low chance (0) of getting admitted. The binarization simplifies the problem into a binary classification task.
Exploratory data analysis (EDA) is carried out using Seaborn to understand the distribution of target classes. The features (independent variables) are then separated from the target variable. The dataset is split into training and test sets using an 75/25 split. A Decision Tree Classifier from the scikit-learn library is employed for training the model on the training set.
Once the model is trained, it is used to predict the admission results for the test data. The performance of the model is evaluated using accuracy score, confusion matrix, and a detailed classification report which includes metrics such as precision, recall, and F1-score. The results are visualized through a confusion matrix display and a decision tree plot, making the decision-making process interpretable and transparent.
Additionally, the model is tested on new, unseen data to predict whether a given student profile would likely be admitted or not. The decision tree itself is visualized using plot_tree(), showcasing how decisions are made based on the input features like GRE, TOEFL, CGPA, and Research.
This project highlights how machine learning can be effectively used in educational data mining to assist institutions in decision-making processes. The model can be improved further by trying other classification algorithms or by optimizing hyperparameters through techniques like grid search or cross-validation. Overall, this project successfully demonstrates the implementation of a supervised learning model for predictive analytics in academic admissions.
