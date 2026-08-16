# California Housing Price Prediction

A machine learning project that predicts **median house values in California** using the California Housing dataset. The project covers data exploration, preprocessing, model training, evaluation, and prediction.

## 📌 Project Overview

The objective of this project is to build a machine learning model that can predict the **median house value** of a California district based on demographic, geographic, and housing-related features.

This project is useful for understanding the complete machine learning workflow:

* Data collection
* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Prediction

## 📊 Dataset

The project uses the **California Housing dataset**, which contains information about different districts in California.

### Features

| Feature       | Description                              |
| ------------- | ---------------------------------------- |
| `MedInc`      | Median income in the district            |
| `HouseAge`    | Median house age in the district         |
| `AveRooms`    | Average number of rooms per household    |
| `AveBedrms`   | Average number of bedrooms per household |
| `Population`  | District population                      |
| `AveOccup`    | Average number of household members      |
| `Latitude`    | Geographic latitude                      |
| `Longitude`   | Geographic longitude                     |
| `MedHouseVal` | Median house value — target variable     |

### Target Variable

`MedHouseVal` — Median house value of the district.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
California-Housing-Prediction/
│
├── data/
│   └── housing.csv
│
├── notebooks/
│   └── California_Housing_Analysis.ipynb
│
├── train.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation

Clone the repository:

```bash
git clone <your-github-repository-url>
cd California-Housing-Prediction
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

Run the training script:

```bash
python train.py
```

If using Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/California_Housing_Analysis.ipynb
```

## 🔄 Machine Learning Workflow

```text
California Housing Dataset
          ↓
Data Loading
          ↓
Data Cleaning & Preprocessing
          ↓
Exploratory Data Analysis
          ↓
Feature Selection
          ↓
Train-Test Split
          ↓
Model Training
          ↓
Model Evaluation
          ↓
House Price Prediction
```

## 🤖 Machine Learning Models

The project can be implemented using multiple regression algorithms, such as:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

The models can be compared using evaluation metrics such as **MAE, MSE, RMSE, and R² Score**.

## 📈 Evaluation Metrics

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

The square root of MSE and provides the error in the same unit as the target.

### R² Score

Measures how well the model explains the variation in the target variable.

## 🔮 Sample Prediction

After training the model, new housing information can be provided to generate a predicted median house value.

```python
prediction = model.predict(new_data)
print("Predicted House Value:", prediction)
```

## 🎯 Key Learning Outcomes

Through this project, you can learn:

* How to perform EDA on a real-world dataset
* How to handle and preprocess housing data
* How regression algorithms work
* How to compare machine learning models
* How to evaluate regression models
* How to build an end-to-end machine learning project using Python

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
* Feature engineering
* Cross-validation
* Model deployment using Flask or FastAPI
* Interactive prediction interface using Streamlit
* Dockerize the application
* Deploy the model on AWS or Azure

## 👩‍💻 Author

**Komal Yadav**

Data Scientist | AI/ML | Generative AI

---

⭐ If you found this project useful, consider giving the repository a star!

