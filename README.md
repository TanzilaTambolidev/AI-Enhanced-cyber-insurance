# AI-Enhanced Cyber Insurance System

This project aims to reduce cyber risks for insurance purposes by developing an AI-enhanced Cyber Insurance system. The system uses machine learning algorithms to analyze cybersecurity risk factors, identify potential dangers, and suggest customized insurance plans tailored to an organization's unique risk profile.

## Features

- **Data Simulation and Preprocessing:**  
  The project simulates a synthetic cybersecurity dataset including features such as the number of incidents, vulnerability scores, intrusion attempts, audit scores, and employee training scores. Data is split into training and testing sets and standardized.

- **Risk Assessment Model:**  
  A Decision Tree classifier is trained to predict a risk category (Low, Medium, or High) based on the risk-related features. The model is evaluated using accuracy, classification report, and a confusion matrix.

- **Insurance Plan Recommendation:**  
  Based on the predicted risk category, the system recommends an insurance plan:
  - Low Risk → Basic Cyber Insurance
  - Medium Risk → Standard Cyber Insurance
  - High Risk → Premium Cyber Insurance

- **Model Deployment:**  
  The final model (including preprocessing) is saved as a pipeline using `joblib` for easy deployment. A Flask API can be built on top of this to serve predictions in real time.

## Dependencies
Python 3.x
numpy
pandas
scikit-learn
matplotlib
seaborn
joblib
Flask (optional, if building an API)

## Acknowledgements
Thanks to the open-source community and the developers of Python libraries such as scikit-learn, pandas, numpy, and Flask.
This project is a demonstration of how AI can be applied to cybersecurity risk assessment and insurance plan customization.

