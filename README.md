# star_classifcation
🌌 Galaxy Classification using Deep Neural Networks (DNN)
📌 Overview

This project implements a Deep Neural Network (DNN) to classify astronomical objects using data from the Sloan Digital Sky Survey (SDSS).

The model learns patterns from astronomical measurements to classify objects into:

⭐ Star
🌌 Galaxy
☄️ Quasar

This project demonstrates a complete end-to-end machine learning pipeline, from data preprocessing to neural network training and evaluation.

📊 Dataset Description

The dataset contains astronomical observations with multiple photometric and positional features.

🔑 Key Features:
alpha: Right Ascension angle
delta: Declination angle
u, g, r, i, z: Photometric filter magnitudes
redshift: Measure of object distance
class: Target label (Galaxy, Star, Quasar)
Additional metadata (e.g., obj_ID, run_ID, etc.)
🧠 Project Workflow
1️⃣ Data Understanding
Loaded dataset
Inspected structure and data types
Identified target and feature columns
2️⃣ Exploratory Data Analysis (EDA)
Statistical summaries
Distribution analysis of features
Visualization of patterns and correlations
Checked class distribution
3️⃣ Data Preprocessing
🔹 Feature Selection
Removed irrelevant columns (IDs and identifiers)
Selected only meaningful predictive features
🔹 Target Mapping
Encoded categorical target (class) into numerical values
🔹 Train-Test Split
Split dataset into training and testing sets
🔹 Feature Scaling
Applied StandardScaler
Normalized features for better neural network performance
4️⃣ Neural Network Design
Built a Deep Neural Network (DNN)
Fully connected Dense layers
Activation functions:
ReLU (hidden layers)
Softmax (output layer)
Dropout layers added to reduce overfitting
5️⃣ Model Compilation
Loss Function: categorical_crossentropy
Optimizer: Adam
Metrics: accuracy
6️⃣ Model Training
Trained on training dataset
Validated using validation split
Monitored accuracy and loss over epochs
7️⃣ Model Evaluation
Evaluated on test dataset
Metrics used:
Accuracy Score
Confusion Matrix
Classification Report
⚙️ Technologies Used
Python 🐍
TensorFlow / Keras 🤖
Pandas 📊
NumPy 🔢
Scikit-learn ⚙️
Matplotlib 📈
