# Rock-vs-Mine-Prediction

Rock vs Mine Prediction for Submarine Navigation

Overview

This project aims to enhance the safety and operational efficiency of submarines by accurately identifying objects detected via sonar as either rocks or mines. This distinction is crucial for military submarines to prepare appropriate responses. The model is trained on the SONAR dataset obtained from Kaggle and utilizes various machine learning techniques to achieve high prediction accuracy.

Dataset

The dataset used in this project is the SONAR dataset from Kaggle. This dataset contains sonar signals bounced off from various surfaces, including rocks and metal cylinders (which are used to simulate mines). The dataset has 208 instances and 60 features representing the sonar signal strength at different angles.

Dataset Source

SONAR Dataset on Kaggle
Project Structure
data/: Contains the dataset and any preprocessing scripts.
notebooks/: Jupyter notebooks used for data exploration, preprocessing, model training, and evaluation.

Installation

To get started with the project, clone the repository and install the necessary dependencies:
bash
Copy code
git clone https://github.com/your-username/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction
pip install -r requirements.txt

Usage

Data Preprocessing:

           Preprocess the SONAR dataset by normalizing and splitting it into training and testing sets.
           Execute the preprocessing scripts or run the corresponding Jupyter notebooks in the notebooks/ directory.
Model Training:

           Train the machine learning models using the preprocessed data.
           Execute the training scripts in the src/ directory or run the training notebooks in the notebooks/ directory.
Model Evaluation:

          Evaluate the performance of the trained models on the test set.
          Visualize the results and metrics using the notebooks in the notebooks/ directory.
Prediction:

          Use the trained model to make predictions on new sonar data.
          Run the prediction scripts in the src/ directory or use the provided notebooks.
          
Models Used

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
Random Forest
Neural Network


Results

The project achieved the following results:

Accuracy: 96%
Precision: 96%


Acknowledgements

   Kaggle for providing the SONAR dataset.
