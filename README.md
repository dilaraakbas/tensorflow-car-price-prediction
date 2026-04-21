Car Price Prediction with TensorFlow
This project demonstrates an end-to-end Deep Learning pipeline to predict car prices using vehicle features. It focuses on regression analysis using a neural network built with the TensorFlow/Keras framework.

📌 Project Overview
The goal of this model is to estimate the market value of a vehicle based on its technical specifications. This is a Regression problem where the output is a continuous numerical value (Price).

🛠 Tech Stack
Framework: TensorFlow / Keras
Data Manipulation: Pandas, NumPy
Preprocessing: Scikit-learn (Scaling & Splitting)
Environment: Jupyter Notebook

📊 Dataset Features
The model analyzes the following attributes to determine the price:
Model Year: The manufacturing year of the vehicle.
Mileage: Total distance driven (KM).
Engine Volume: Engine displacement (cc).
Horsepower: Engine power (HP).
Vehicle Age: Calculated age from the current year.

🧠 Model Architecture
The neural network consists of a Sequential structure:
Input Layer: Receives the 5 vehicle features.
Hidden Layers: Two dense layers with ReLU activation for non-linear learning.
Output Layer: A single neuron with no activation function (standard for regression).

📈 Performance Analysis & Insights
Influential Features: Vehicle price is most strongly correlated with Model Year and Mileage. The model captures these linear trends effectively.
Prediction Capacity: The model performs best on "average" vehicle types (e.g., 5-10 years old with standard mileage).
Limitations: The margin of error may increase for luxury vehicles or cars with accident history, as these specific variables were not included in the training set.

📋 Executive Summary
Average Prediction Error: The model operates with a stable Mean Absolute Error (MAE).
Operational Use: Suitable for preliminary price estimations in the second-hand market.
Future Improvements: Adding features like "Fuel Type" or "Damage Records" could significantly increase accuracy.
