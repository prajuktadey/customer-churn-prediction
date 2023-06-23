
Customer Churn Detection App
============================

This web application is designed to predict customer churn using an Artificial Neural Network (ANN). The app is built using Streamlit, a Python library for creating interactive web applications.

Live Demo:
---------

A live demo of the application is available at <https://prajuktadey-customer-churn-prediction.streamlit.app/>.

Overview:
--------

Customer churn refers to the phenomenon of customers discontinuing their business relationship with a company. Predicting customer churn is crucial for businesses to understand customer behavior and take proactive measures to retain them.

This app provides a user-friendly interface to input customer data and predict the likelihood of churn using an Artificial Neural Network model. The app takes various customer-related features as inputs, such as customer demographics, usage patterns, and service history, and generates a churn prediction based on the trained model.

Usage:
-----

To run the application locally, follow these steps:

1.  Clone the repository:

    `git clone https://github.com/your-username/customer-churn-detection-app.git`

2.  Install the required dependencies:
3.  
    `pip install -r requirements.txt`

4.  Run the Streamlit app:

    `streamlit run main.py`

5.  Access the app in your web browser by visiting `http://localhost:8501`.

Project Structure
-----------------

The project directory contains the following files and directories:

-   `app.py`: The main application file that defines the Streamlit app and its user interface.
-   `model.sav`: The pre-trained ANN model used for churn prediction.
-   `requirements.txt`: The list of required Python packages and their versions.
   
Dependencies:
------------

The following Python packages are used in this project:

-   Streamlit: `streamlit`
-   NumPy: `numpy`
-   Pandas: `pandas`
-   Scikit-learn: `scikit-learn`
-   TensorFlow: `tensorflow`
-   Keras: `keras`

You can find the complete list of dependencies and their versions in the `requirements.txt` file.
