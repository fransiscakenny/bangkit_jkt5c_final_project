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

2. WEB APPLICATION CREATION

This folder has everything necessary to run the web-application locally, this web-application is ready to deploy.
We have deployed our version, it can be found here: https://bangkit-demo.herokuapp.com/

Everything within this folder is taken from our member, Winson Wijaya's original GitHub Repo: https://github.com/winson121/bangkit_final_webapp/tree/master

How to replicate this Web Application:
1. Install all the required packages in the requirements.txt
2. Create the Flask Application as shown in the app.py
3. Make sure you have the necessary JavaScript, HTML & CSS files.
4. Use the command line: flask run, to ensure your Flask App is running properly. 
5. Read more on this link: https://www.geeksforgeeks.org/deploy-python-flask-app-on-heroku/ to deploy the Flask App to Heroku.
