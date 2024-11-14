# Calorie-Predictor
This project uses a machine learning model to predict the calories burned during exercise based on user inputs such as heart rate, exercise duration, weight, height, age, and body temperature.
Features
•	User Inputs: Users can input personal details like age, height, weight, exercise duration, heart rate, and body temperature.
•	Model: The project uses the XGBRegressor model to predict the calorie burn based on the provided input data.
•	Data Scaling: Data is standardized using StandardScaler to improve prediction accuracy.
•	Visualization: Displays an image with a caption to illustrate the application.
Data
•	Calories Data: The target data for calories burned, provided in calories.csv.
•	Exercise Data: The feature data for each exercise session, provided in exercise.csv.
How It Works
1.	Data Processing: Loads and scales exercise data.
2.	Model Training: Trains an XGBoost regression model on the provided data.
3.	Prediction: Predicts the calorie burn for the user's inputs.
4.	Display Results: Displays the predicted calories burned.
Requirements
•	Python libraries: streamlit, pandas, numpy, scikit-learn, xgboost, PIL
