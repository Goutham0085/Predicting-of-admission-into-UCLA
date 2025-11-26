# Predicting Admission into UCLA

This repository contains a complete web application that predicts the likelihood of admission into UCLA based on various applicant features. The project includes a **frontend (React.js)**, **backend (Express.js)**, and **Flask API** for making predictions using a trained machine learning model.

## Table of Contents

- [Project Overview](#project-overview)
- [Folder Structure](#folder-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

The UCLA Admission Predictor helps students estimate their chances of admission based on input features such as GRE scores, TOEFL scores, GPA, and research experience. The model was trained using machine learning techniques and deployed via a REST API.



## Usage
Once all services are running:
- Open the frontend in a browser.
- Enter applicant details.
- Click **Predict** to get an admission probability.

## Model Details
The prediction model was trained using:
- **Features:** GRE, TOEFL, University Rating, SOP, LOR, CGPA, Research
- **Final Model:** Linear Regression (best accuracy after hyperparameter tuning)
- **Evaluation Metrics:** MSE, R2 Score

## Results
The model provides a probability score (0-100%) indicating the likelihood of admission.

## Contributing
Contributions are welcome! Open an issue or submit a pull request if you want to improve the project.

