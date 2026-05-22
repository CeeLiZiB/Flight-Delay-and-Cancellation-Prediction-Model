# Flight Delay and Cancellation Prediction Model

This project analyzes the relationship between weather conditions and flight delays/cancellations using machine learning models. Weather and flight datasets were merged and cleaned to build predictive models for classifying flights as on-time, delayed, or cancelled.

## Features include:
  -  Flight and weather dataset integration
  -  Data cleaning and preprocessing
      - Removing/replacing null values
      - Standardizing string and numeric data
      - Converting incorrect or inconsistent data types
      - Detecting and handling outliers
  -  Feature engineering from timestamps
  -  Built preprocessing and training pipelines using Scikit-learn and imbalanced-learn
  -  Handling imbalanced classes using SMOTE
  -  Machine learning classification models:
      - Logistic Regression
      - Random Forest
      - Gradient Boosting
  - Model performance evaluation using:
      - Accuracy
      - F1-score
      - Precision
      - Recall
      - Confusion matrices
   
## Dataset Information
The project uses:
  - Flight operational data
    - Sources:
      - https://transtats.bts.gov/DL_SelectFields.aspx?gnoyr_VQ=FGK&QO_fu146_anzr=b0-gvzr
      - https://rowzero.com/datasets/us-flights-dataset
  - Historical weather observations
    - Source:
      - https://mesonet.agron.iastate.edu/request/download.phtml?network=CO_ASOS 

Key features include:
  - Departure delay
  - Carrier
  - Origin/Destination airports
  - Temperature
  - Wind speed
  - Visibility
  - Humidity

## Results

The Random Forest model achieved the best overall performance:

<img width="966" height="159" alt="image" src="https://github.com/user-attachments/assets/4fae8b01-b286-440d-9629-b5a9bf846b21" />

## Technologies Used

  - Python
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - imbalanced-learn (SMOTE)
  - Jupyter Notebook
  - Git/GitHub

## Authors

Ciara Banks
Pamela Dowuona
Maria Ghobrial
Julie Tat
Phuong Khanh Ton

