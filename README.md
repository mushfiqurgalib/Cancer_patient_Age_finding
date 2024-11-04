# Cancer Patient Age Estimation Using HOG, SIFT, and CT Images

## Overview
This project focuses on developing a machine learning model to estimate the age of cancer patients based on computed tomography (CT) images using advanced feature extraction techniques, specifically Histogram of Oriented Gradients (HOG) and Scale-Invariant Feature Transform (SIFT). By analyzing the features extracted from CT scans, we aim to build a reliable age estimation system that can assist in personalized cancer treatment plans.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Data Collection](#data-collection)
- [Methodology](#methodology)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features
- **CT Image Analysis**: Utilizes CT images for effective age estimation in cancer patients.
- **Feature Extraction**: Implements HOG and SIFT for robust feature extraction from medical images.
- **Machine Learning Model**: Trains a regression model to predict patient age based on extracted features.
- **Evaluation Metrics**: Provides various metrics to evaluate the model's performance.

## Installation
To run this project, ensure you have the following prerequisites installed:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cancer-age-estimation.git
   cd cancer-age-estimation
Create a virtual environment (optional but recommended):


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

pip install -r requirements.txt
## Data Collection
The dataset used for this project consists of CT images of cancer patients along with their corresponding ages. The images were obtained from [insert data source or mention if it’s a public dataset], ensuring compliance with ethical standards and patient confidentiality.

Data Preparation
Instructions for data preprocessing, including normalization and resizing of CT images, are provided in the Jupyter notebook. The dataset is split into training and testing sets to facilitate model evaluation.

## Methodology
Feature Extraction:

HOG: Compute the HOG features from CT images to capture the distribution of gradients.
SIFT: Utilize SIFT to detect and describe local features in the images, providing robustness to scaling and rotation.
Model Training:

Train a regression model (e.g., Random Forest, Support Vector Regression) using the extracted features and corresponding ages of the patients.
Age Prediction:

Use the trained model to predict the age of new cancer patients based on their CT images.
## Usage
To use the notebook for estimating cancer patient age, follow these steps:

Open the Jupyter notebook:


jupyter notebook
Run the notebook cells sequentially, which are organized into sections for feature extraction, model training, and age prediction.

Example usage:

Input a CT image of a cancer patient into the specified cell.
Execute the prediction cell to obtain the estimated age based on the trained model.
## Results
The results section of the notebook includes:

A comparison of predicted ages versus actual ages with visualization (e.g., scatter plots).
Evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared values to assess model performance.
## Contributing
Contributions are welcome! To contribute to this project, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature/YourFeature).
Create a pull request.
## License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Proma Chowdhury & Shafiq-us Saleheen for their contributions and support throughout this project.
The medical dataset providers for making their data publicly available.
The open-source community for libraries and tools that facilitated image processing and machine learning.
