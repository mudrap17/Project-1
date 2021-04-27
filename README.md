# Project-1
BREAST CANCER CLASSIFICATION PROJECT

Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers. And we build a classification model to identify the IDC and non IDC images.

You can find the dataset for the project at https://www.kaggle.com/paultimothymooney/breast-histopathology-images

You can download the dataset in the original subfolder of the datasets folder.

The build_dataset.py file will then divide the dataset into training,validation and testing sets with each having 0 and 1 subfolders denoting non IDC and IDC.

The cancernet.py will provide the convolutional neural networks model used for training.

The train_model.py will train the CNN using the training and validation datasets and evaluate the accuracy of the model using the testing dataset.
