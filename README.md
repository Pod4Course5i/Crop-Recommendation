 **Crop-Recommendation**

1) The code is locally developed on VS Code and the frontend was developed using Streamlit which were pushed to the github repository.
2) Jenkins is used for the continuous integration and continuous developement.
3) Jenkins, Docker and all the required dependencies were installed on EC2 machine.
4) Github is being integrated to jenkins using an API called github webhooks & AWS is connected to jenkins using the AWS credentials.
5) The docker image is being built, pushed to ECR and run using a pipeline script on jenkins.
6) Finally the app is deployed on Elastic Container Service.

![CropRecommender](https://github.com/Pod4Course5i/Crop-Recommendation/assets/125888203/4a664ffa-6be6-469f-bc05-1ad56b2083f5)
