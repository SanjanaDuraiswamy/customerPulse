#  Customer Churn Prediction using ANN

## Overview

This project is a customer churn prediction system built using Artificial Neural Networks (ANN). It takes customer data as input and predicts whether a customer is likely to leave the service (churn) or stay. The model is trained on the **Churn\_Modelling.csv** dataset and deployed using **Streamlit** for easy interaction.

## Features

- **Data Preprocessing:** Handling categorical data using Label Encoding and One-Hot Encoding.
- **Feature Scaling:** StandardScaler from scikit-learn.
- **Model Training:** Using TensorFlow and Keras to build an ANN.
- **Hyperparameter Tuning:** GridSearchCV for finding the best model parameters.
- **Model Saving & Loading:** Using pickle and `.h5` format.
- **Interactive UI:** Built using Streamlit for easy model interaction.

## Tech Stack 🛠️

The project is built using the following technologies:

- **Frontend:** Streamlit 
- **Backend:** TensorFlow
- **Machine Learning:** scikit-learn, TensorFlow 
- **Data Processing:** Pandas, NumPy 
- **Preprocessing:** StandardScaler, LabelEncoder, OneHotEncoder 
- **Model Format:** `.h5` (Keras Model)
- **Version Control:** Git & GitHub 

## Installation

Clone the repository:

```sh
git clone https://github.com/SanjanaDuraiswamy/customerPulse.git
cd customerPulse
```

Create a virtual environment and activate it:

```sh
python -m venv env
# For Windows
env\Scripts\activate
# For Mac/Linux
source env/bin/activate
```

Install the required dependencies:

```sh
pip install -r requirements.txt
```

## Dataset

The project uses **Churn\_Modelling.csv**, which contains customer details, including:

- Credit Score
- Geography
- Gender
- Age
- Balance
- Estimated Salary
- Exited (Target variable: 1 for churn, 0 for non-churn)

## Training the Model

Run the Jupyter Notebook:

```sh
jupyter notebook
```

Open `hyperparametertuningann.ipynb` to train and tune the ANN model.

## Running the Streamlit App

After training, you can test the model using Streamlit:

```sh
streamlit run app.py
```

This will launch an interactive web UI where you can input customer details and get churn predictions.

## Model Deployment

The model can be deployed using:

- **Streamlit Cloud**
- **Heroku / AWS / GCP (Future Scope)**

## Usage

- Modify `app.py` to enhance UI/UX.
- Update `requirements.txt` if adding new libraries.
- Train with different architectures for better accuracy.

## Contributing

Feel free to fork the repo and submit PRs for improvements!

## License

This project is licensed under the MIT License.

---

✅ **Project Completed & Ready for Deployment** 🚀

