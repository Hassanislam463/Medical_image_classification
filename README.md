## Medical Image Analysis and Classification

# Documentation

Our project directory has 9 different files and folders. 

## 1. breastmnist

This folder contains,

1. The model weights with optimal performance, over a range of epochs, for each of our model created. These are named as "self_model.weights.best.hdf5","aug_model.weights.best.hdf5"and "model_resampled.weights.best.hdf5".

2. The notebook for analysis and creation of model using breastmnist dataset, saved as "breastmnist.ipynb".

3. Data Folder containing the breastmnist dataset in separates folders for train,test and validation splits respectively.

## 2. bloodmnist

This folder contains,

1. The model weights with best optimal performance over a certain range of epochs, for each of our model created. These are named as "self_model.weights.best.hdf5","aug_model.weights.best.hdf5"and "vgg_model.weights.best.hdf5".

2. The notebook for analysis and creation of model using breastmnist dataset, saved as "bloodmnist.ipynb".

3. Data Folder containing the bloodmnist dataset in separate folders for train,test and validation splits respectively.

## 3. Blood Cell Sample Images

This folder contains blood cells sample images for testing purposes.

## 4. Breast Cancer Sample Images

This folder contains breast cancer sample images for testing purposes.

## 5. Blood cell labelled samples

This folder contains labelled blood cells types for testing purposes.

## 6. model_blood.h5

This is the best model selected for the blood cell classifier.

## 7. model_breast.h5

This is the best model selected for breast cancer model.

## 8. requirements.txt

This file contains the dependencies needed to run our web application.

## 9. app.py

This file contains the code needed to run our best models as web application.

# RUNNING OUR WEB APPLICATION

To run the web application, download all dependencies from requirements.txt and then run following command in the cli of project directory:

"streamlit run app.py"


