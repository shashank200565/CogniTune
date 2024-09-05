# CogniTune

This is a project we had made for MUJ HackX 2.0 on the problem statement - "Brain Signal Analysis for Attention identification (Powered by CDAC)"

We Made use of 3 Datasets we found on Kaggle , them being :

1st Dataset - https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-mental-state 
This is a dataset of EEG on different patients which we further used to predict the attention levels of the patients, resulting in a model with accuracy of 85%.

2nd Dataset - https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions
This Dataset also contains signals of different EEG patterns of patients, for this model we achieved an accuracy of 99%.

3rd Dataset - https://www.kaggle.com/datasets/naddamuhhamed/sleepy-driver-eeg-brainwave-data
For this dataset we went with something applicational. It contains the EEG signals of drivers and predicts whether they are sleepy or attentive. For this model we got an accuracy of 80%.

For all of the 3 Models we first used 'train_test_split' to split the data into training and testing set, then we used 'Standard Scaler' to scale the data in the dataset. Then we made use of the 'Principal Component Analysis' Algorithm which is an unsupervised learning model that helps in dimensional minimization for a dataset. What this does is it makes it easier for prediction. Then we tried several algorithms like 'Decision Tree', followed by 'Support Vector Machines' but the best fit we found for our models was the 'Random Forest' Model. We then trained and predicted outcomes using this model. For performance metrics we used Mean Absolute Error and Mean Squared Error for the errors and classification report for the accuracy, precision, recall and F1 score.
