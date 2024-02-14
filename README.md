
Car Price Prediction using Gradient Boosting Algorithm
This project aims to predict car prices using the Gradient Boosting algorithm. The dataset contains various features such as the name of the car, its location, year of manufacture, kilometers driven, fuel type, transmission, owner type, mileage, engine capacity, power, number of seats, and price.

Dataset
The dataset consists of 6019 entries and 12 columns:

Name: Name of the car.
Location: Location where the car is being sold.
Year: Year of manufacture.
Kilometers_Driven: Total kilometers driven by the car.
Fuel_Type: Type of fuel used by the car (e.g., Petrol, Diesel, CNG).
Transmission: Type of transmission (e.g., Manual, Automatic).
Owner_Type: Type of ownership (e.g., First Owner, Second Owner).
Mileage: Mileage of the car (in kilometers per liter).
Engine: Engine capacity of the car (in cc).
Power: Power of the car (in bhp).
Seats: Number of seats in the car.
Price: Selling price of the car.
Methodology
Data Preprocessing: The dataset is cleaned and preprocessed to handle missing values, categorical variables, and feature scaling.

Feature Engineering: Relevant features are selected, and new features may be created to improve model performance.

Model Training: The Gradient Boosting algorithm is trained on the processed dataset to learn the patterns and relationships between the features and the target variable (Price).

Model Evaluation: The trained model is evaluated using appropriate metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess its performance.

Prediction: The model is then used to predict car prices for unseen data or real-world scenarios.

Requirements
Python 3.x
Required Python packages (e.g., pandas, scikit-learn, xgboost)
