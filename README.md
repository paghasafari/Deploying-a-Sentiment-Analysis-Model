# About

The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker.

# Instructions

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks) to create a sentiment analysis web application. 

The SageMaker Project notebook pursues the following steps to deploy and use the model.  

1- Download or otherwise retrieve the data.
2- Process / Prepare the data.
3- Upload the processed data to S3.
4- Train a chosen model.
5- Test the trained model (typically using a batch transform job).
6- Deploy the trained model.
7- Use the deployed model.
