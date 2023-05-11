### 1. Prediction 

Develop code for crop recommender with frontend parameters using Streamlit on local
Create a repository on GitHub
Use Jenkins to create a webhook between GitHub and Jenkins for a CI/CD pipeline
Establish Jenkins connection in the EC2 instance for predictions
Take weights from .pkl file in S3 bucket outside EC2 instance for the main application
Choose the best weight file for accuracy and use it for prediction and display in frontend
Use Nginx for reverse proxy, load-balancing, and caching to enhance stability and performance

### 2. Re-training 

Use AWS Lambda service to initiate EC2 instance periodically for retraining with new data
Push the new model file to S3 bucket for downloading by another script for prediction
Stop the other EC2 instance after retraining is complete
This process completes the loop for retraining the model with new data.

### Architecture 

