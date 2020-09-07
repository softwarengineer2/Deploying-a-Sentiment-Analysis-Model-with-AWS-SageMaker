# Deploying-a-Sentiment-Analysis-Model-with-AWS-SageMaker

# Project Overview
Welcome to the SageMaker deployment project! In this project you will construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. You will create this model using Amazon's SageMaker service. In addition, you will deploy your model and construct a simple web app which will interact with the deployed model.

# Project Instructions
The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

# General Outline
Recall the general outline for SageMaker projects using a notebook instance.

Download or otherwise retrieve the data.
Process / Prepare the data.
Upload the processed data to S3.
Train a chosen model.
Test the trained model (typically using a batch transform job).
Deploy the trained model.
Use the deployed model.