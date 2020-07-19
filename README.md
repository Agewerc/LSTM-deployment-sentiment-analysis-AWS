# Machine Learning Deployment using AWS SageMaker

This repository contains the code associated with a project developd under the udacity deep learning degree. We train and deploy a PyTorch **sentiment analysis** model of applied in comments of films from the `IMDb dataset`. Deployment gives you the ability to use a trained model to analyze new, user input. We build a model, deploy it, and create a gateway for accessing it from a website.


![Imgur](https://i.imgur.com/BppgLK3.png)


## Dataset

This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. There is a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. Raw text and already processed bag of words formats are provided. 


## Steps

1. Downloading the data
2. Preparing and Processing the data
3. Upload the data to S3
4. Build and Train the PyTorch Model
5. Testing the model
6. Deploy the model for testing
7. Use the model for testing
8. Deploy the model for the web app
