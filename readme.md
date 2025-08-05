# Real Estate Price Prediction — End-to-End Data Science Project

This data science project is a comprehensive, step-by-step walkthrough on how to build an **end-to-end real estate price prediction system** using the **Bangalore Home Prices Dataset** from Kaggle dataset. It simulates a real-world workflow, covering everything from data cleaning and preprocessing to deploying a machine learning model via a web API using **Python Flask**.

## Project Overview

The objective of this project is to **predict housing prices** based on various features like location, square footage, number of bedrooms (BHK), and bathrooms. We use **Linear Regression** as our primary algorithm, and incorporate best practices in data science and machine learning throughout the development process.

##  Key Highlights

###  Phase 1: Model Building

- **Data Collection**: Dataset sourced from Kaggle (Bangalore home prices).
- **Data Preprocessing**:
  - Handling missing values
  - Feature engineering (e.g., converting categorical variables)
  - Outlier detection and removal
  - Dimensionality reduction
- **Model Development**:
  - Linear Regression using **scikit-learn (sklearn)**
  - GridSearchCV for **hyperparameter tuning**
  - **K-Fold Cross Validation** for model evaluation
- **Model Persistence**: Saving the trained model using `pickle`

###  Phase 2: Model Deployment

- Developing a **Flask-based HTTP API** to serve the trained model
- API allows users to input house features and get real-time price predictions

## Tools & Technologies Used

| Category             | Tools / Libraries                  |
|----------------------|------------------------------------|
| Programming Language | Python                             |
| Data Manipulation    | NumPy, Pandas                      |
| Data Visualization   | Matplotlib                         |
| Model Building       | Scikit-learn (sklearn)             |
| Deployment           | Flask                              |
| IDEs Used            | Jupyter Notebook, VS Code, PyCharm |

---

## 📁 Project Structure




