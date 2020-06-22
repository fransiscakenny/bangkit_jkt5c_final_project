# bangkit_jkt5c_final_project

This repository consists of the code for training, deploying, and testing the model, as well as the code to create the application and call the deployed model from AI Platform. 

1. MODEL CREATION
Required to have before running:

Makeup Or No Makeup Dataset from Kaggle: https://www.kaggle.com/petersunga/make-up-vs-no-make-up/kernels
For OpenCV, download: deploy.prototxt and weights.caffemodel file
To see our baseline model creation, open this -> makeup_final_project.ipynb Exp #1: Baseline Model

There's one with MobileNetV2
And one without MobileNetV2
To see our final model, look at this collab file -> train_makeupmodel_opencv_5.ipynb

Pick model_2
There will be tutorial on how to save the model as a SavedModel
How to load the SavedModel and use it for prediction
How to save the model in GCS
How to save create an AI Platform model and version using that saved in GCS model
To test the API created in the previous code:

test_makeup_api.ipynb Code to test the AI Platform API

1. WEB APPLICATION CREATION
