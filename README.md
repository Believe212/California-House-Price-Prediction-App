# California-House-Price-Prediction-App
This project is an end-to-end machine learning application that predicts housing prices based on geographic and socio-economic features from the California housing dataset.

🚀 Project Overview
Built a Linear Regression model using Scikit-learn
Established a baseline prediction (~206,644) using the mean house value
Improved performance using a full ML pipeline with preprocessing
Deployed the model as an interactive web app using Streamlit

🧠 Key Features
Handles categorical data (ocean_proximity) using OneHotEncoder
Uses ColumnTransformer to combine categorical and numerical features
Accepts real-time user input and returns predicted house prices
Fully deployed and accessible via web browser

📊 Model Performance
RMSE: ~69,298
Baseline (mean prediction): ~206,644

🔍 Insights
Houses located closer to the ocean tend to have higher prices
Median income is a strong predictor of house value

🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn (Pipeline, LinearRegression, OneHotEncoder, ColumnTransformer)
Streamlit (for deployment)
