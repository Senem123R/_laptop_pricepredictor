💻 Laptop Price Predictor Web Application

A Machine Learning based web application that predicts the price of a laptop based on its specifications such as RAM, weight, company, CPU, GPU, operating system, and more.

This project is built using:

🐍 Python

🌐 Flask

📊 NumPy

🤖 Machine Learning (Pickle Model)

🎨 HTML & CSS

🚀 Features -----

User-friendly web interface

Predicts laptop price instantly

Uses trained ML model (predictor.pickle)

Supports multiple laptop brands and configurations

Converts predicted value into LKR currency

🖥️ Input Parameters ----

The model takes the following inputs:

RAM (GB)

Weight (Kg)

Company (Acer, Apple, Asus, Dell, HP, Lenovo, MSI, Toshiba, Other)

Type (Gaming, Ultrabook, Notebook, etc.)

Operating System (Windows, Mac, Linux, Other)

CPU (Intel i3, i5, i7, AMD, Other)

GPU (Intel, AMD, Nvidia)

Touchscreen (Yes/No)

IPS Display (Yes/No)

📂 Project Structure ----

Laptop-Price-Predictor/ │ ├── app.py ├── model/ │ └── predictor.pickle ├── static/ │ └── style.css ├── templates/ │ └── index1.html └── README.md

⚙️ How It Works-----

User enters laptop specifications

Flask collects form data.

Categorical values are converted into one-hot encoded format.

The trained machine learning model predicts the price.

🧠 Machine Learning Model ----

The model is saved using pickle.

It loads inside the prediction() function.

Feature engineering includes: Numeric features, Boolean features, One-hot encoding for categorical features, The result is displayed in LKR.
