 Heart Disease Prediction using ANN (Sigmoid)
This project uses an Artificial Neural Network (ANN) to predict the presence of heart disease based on basic medical features. It's a text-based model, with no preprocessing or feature scaling — raw values are used directly for prediction.
📄 Dataset

Source: UCI Cleveland Heart Disease Dataset
Features Used:
age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal
Target:
0 → No heart disease
1 → Heart disease present


🧠 Model Details
Model: Simple ANN (Artificial Neural Network)
Activation: Sigmoid
Input: 13 features (used directly)
Output: Single neuron (sigmoid output → probability)

✅ What This Project Does
Loads heart disease data
Uses ANN to train on 13 features
Accepts new user input (in the same format)
Outputs prediction as:
0 → No heart disease
1 → Heart disease likely

