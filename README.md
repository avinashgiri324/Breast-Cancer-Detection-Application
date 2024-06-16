## Introduction
This project aims to build a Breast Cancer Detection application using a machine learning model. The application utilizes the XGBoost classifier to predict whether a breast tumor is malignant or benign based on certain diagnostic features. The project is deployed locally using Flask and features a simple HTML-based GUI.

## Project Goal
The primary goal of this project is to provide an easy-to-use web application that helps in early detection of breast cancer. Early detection can significantly improve treatment outcomes and survival rates.

## Dataset
The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which includes features computed from digitized images of fine needle aspirate (FNA) of breast mass. The dataset contains the following:
- Features: Various attributes of the cell nuclei present in the image.
- Target: Binary classification indicating whether the tumor is benign (0) or malignant (1).

## Machine Learning Model
The machine learning model used in this project is the XGBoost classifier, chosen for its high performance and accuracy. The model was trained and evaluated using the following steps:
1. **Data Preprocessing:** Handling missing values, feature scaling, and splitting the dataset into training and testing sets.
2. **Model Training:** Training the XGBoost classifier on the training data.
3. **Model Evaluation:** Evaluating the model's performance using accuracy, precision, recall, and F1 score.

## Web Application
The web application is built using Flask and provides a user-friendly interface for inputting diagnostic features and obtaining predictions. The steps to run the web application are:
1. **Start the Flask server:** The Flask server hosts the web application locally.
2. **Input Features:** Users can input diagnostic features through the HTML form.
3. **Get Prediction:** The application returns the prediction indicating whether the tumor is benign or malignant.

## Results and Findings
The XGBoost classifier achieved high accuracy and performance metrics on the test data, making it a reliable model for breast cancer detection. The web application successfully integrates this model to provide real-time predictions based on user inputs.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Flask
- HTML/CSS
- Jupyter Notebook

## Contributing
Contributions are welcome! 
