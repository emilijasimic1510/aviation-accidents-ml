Aviation Accidents ML Classifier

This project uses historical aviation accident data to predict whether an accident was fatal or non-fatal, using machine learning models such as Random Forest and Logistic Regression.
Project Structure

aviation-ml/
│
├── aviation_accidents.csv   # Dataset
├── main.py                  # Main Python script with the complete pipeline
├── README.md                # Project documentation

Technologies Used

    Python 3.x

    Pandas

    NumPy

    scikit-learn

    Matplotlib

    Seaborn

Project Workflow

    Data Loading

    Data Cleaning and Preprocessing (handling or removing missing values)

    Categorical Data Encoding

    Feature Scaling / Normalization

    Train/Test Split

    Model Training:

        Random Forest

        Logistic Regression

    Model Evaluation:

        Confusion Matrix

        Classification Report

        Accuracy Score

    Visualization:

        Missing values heatmap

        Model accuracy comparison

        Feature importance

        Fatal vs. non-fatal accident distribution

        Most common aircraft types and locations

        Passenger count vs. fatalities scatter plot

        Yearly accident and fatal crash trends

Results

    Both models achieved 100% accuracy on this dataset, which may indicate overfitting due to the small number of examples.

    Random Forest was used to determine feature importance.

Example Visualizations

    Missing values heatmap

    Model performance comparison

    Feature importance bar plot

    Fatal vs. non-fatal crash distribution

    Most common aircraft types and locations

    Passenger count vs. fatalities scatter plot

    Yearly trends of accidents and fatal crashes

Dataset Overview

The dataset includes information about:

    Accident date and location

    Aircraft type

    Number of people aboard

    Number of fatalities and ground casualties

    Whether the accident was fatal or not

Notes:

    The project includes additional dummy records with no fatalities to help balance the target class Fatal = 0.

    In the future, the Summary column could be processed using NLP techniques for deeper analysis.

Author

Emilija Simić
Year: 2025
