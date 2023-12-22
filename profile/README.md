# RoadToFit Organization - Discover your perfect body

An android mobile app that aims to provide assistance in maintaining the ideal body composure, state, as well as nutritional needs.

## Introduction

As technology improves, people tend to stay in front of computers or laptops for long periods. One of the challenges that this brings is maintaining a balanced, optimal body state, and making sure our body posture is ideal.

## Components

1. [RoadToFit Machine Learning](https://github.com/RoadToFit/RoadtoFit-ML)
2. [RoadToFit Backend](https://github.com/RoadToFit/RoadtoFit-be)
3. [RoadToFit Mobile App](https://github.com/RoadToFit/RoadtoFit-MD)

## Machine Learning

Created using Tensorflow and Scikit-learn, our machine learning team developed 3 models:

- **Body classifier** - Uses _Convolutional Neural Network_ (CNN) to determine the user's body class
- **Activities recommendation** - Uses _Decision Tree_ to recommend activites based on the intensity
- **Food recommendation** - Uses _K-Nearest Neighbors_ (KNN) to recommend meals based on required calories and body state

## Cloud Computing

Our cloud computing team developed 2 separate backends with different purpose:

- **Consumer backend** - Developed using NodeJS Express framework, used to serve client request and store data
- **Machine learning backend** - Developed using Python FastAPI framework, used to host machine learning models and serve machine learning request

The deployment uses Google Cloud Platform (GCP) with these services:

- **Google Cloud Run** - Used to deploy both consumer backend and machine learning backend
- **Google Cloud Storage** - Used to store client data e.g. images
- **Google Compute Engine** - Used to host our SQL database solution
- **Artifact Registry** - Used in combination with Github Action for our CI/CD pipeline

## Mobile Development

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
