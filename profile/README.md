# RoadToFit Organization - Discover your perfect body

An android mobile app that aims to provide assistance in maintaining the ideal body composure, state, as well as nutritional needs.

## Introduction

As technology improves, people tend to stay in front of computers or laptops for long periods. One of the challenges that this brings is maintaining a balanced, optimal body state, and making sure our body posture is ideal.

## Components

1. [RoadToFit Machine Learning](https://github.com/RoadToFit/RoadtoFit-ML)
2. [RoadToFit Backend](https://github.com/RoadToFit/RoadtoFit-be)
3. [RoadToFit Mobile App](https://github.com/RoadToFit/RoadtoFit-MD)

### Machine Learning

Created using Tensorflow and Scikit-learn, our machine learning team developed 3 models:

- **Body classifier** - Uses _Convolutional Neural Network_ (CNN) to determine the user's body class
- **Activities recommendation** - Uses _Random Forest_ to recommend activites based on the intensity
- **Food recommendation** - Uses _K-Nearest Neighbors_ (KNN) to recommend meals based on required calories and body state

### Cloud Computing

Our cloud computing team developed 2 separate backends with different purpose:

- **Consumer backend** - Developed using NodeJS Express framework, used to serve client request and store data
- **Machine learning backend** - Developed using Python FastAPI framework, used to host machine learning models and serve machine learning request

The deployment uses Google Cloud Platform (GCP) with these services:

- **Google Cloud Run** - Used to deploy both consumer backend and machine learning backend
- **Google Cloud Storage** - Used to store client data e.g. images
- **Google Compute Engine** - Used to host our SQL database solution
- **Artifact Registry** - Used in combination with Github Action for our CI/CD pipeline

### Mobile Development

Our mobile development team created an android application consisting of these features:

- Welcome page
- Register page
- Login page
- Home page
- Profile page
- Body classifier page
- Food and activity recommendation page

## Development process

Our development process is divided into each team:

### Machine Learning

In order to create the machine learning model, our team followed these steps:

1. Choose the appropriate model to do the prediction
2. Find the correct dataset to train the model
3. Train the model and test the prediction result
4. Generate pre-processing step for the input
5. Export the model into a binary file (e.g. pickle or joblib), ready to be loaded by the cloud computing team

### Cloud Computing

In order to create and deploy the backend service, our team followed these steps:

1. Choose the appropriate technology stack to use, in our case, NodeJS Express and Python FastAPI
2. Develop an API service for both consumer and machine learning backend
3. Choose cloud computing services to use within Google Cloud Platform
4. Create a CI/CD pipeline for smoother deployment process
5. Test the deployment result
6. Notify mobile development team of the deployed API service

### Mobile Development

In order to create the android mobile application, our team followed these steps:

1. Design the UI/UX and map out the features required
2. Develop each page according to the design
3. Integrate the application with the deployed backend service
4. Test the mobile application

## Created By

| Name                      | Bangkit ID  | Learning Path             |
| ------------------------- | ----------- | ------------------------- |
| Al Diras Pradiptha        | M299BSY0648 | Machine Learning Cohort   |
| Achmad Fadli              | M008BSY0043 | Machine Learning Cohort   |
| Ikmal Alfaozi             | M002BSY0509 | Machine Learning Cohort   |
| Yakobus Iryanto Prasethio | C002BSY3073 | Cloud Computing Cohort    |
| Eiffel Aqila Amarendra    | C002BSY3384 | Cloud Computing Cohort    |
| Nikolaus Evan Dewanto     | A200BSY2596 | Mobile Development Cohort |
| Rivandi                   | A314BSY2228 | Mobile Development Cohort |
