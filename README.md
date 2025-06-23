# python_reg

🏠 House Price Prediction using Linear Regression
This project explores a real estate dataset and builds a regression model to predict housing prices based on various socioeconomic and geographical features. 

The notebook includes EDA, data preprocessing, and model evaluation using key regression metrics.

📁 Project Structure

ANWAR_DATA_HOUSE.ipynb: The main Jupyter notebook for:

Exploratory Data Analysis

Feature selection and visualization

Linear Regression modeling

Model evaluation and residual diagnostics

📦 Dataset

Source: housing.csv

Features include:

avg_area_income: Average income of residents in the area

avg_area_house_age: Average age of houses in the area

avg_area_number_of_rooms: Average number of rooms per house

avg_area_number_of_bedrooms: Average number of bedrooms per house

area_population: Population of the area

price: Target variable – price of the house

🧠 Model

Model Used: LinearRegression() from scikit-learn

Training/Test Split: 80/20

Evaluation Metrics:

R² Score (Train & Test)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

📊 Visualizations

Distribution and boxplots for features

Residual plot for model diagnostic


📌 Key Findings

The linear model performs reasonably well, with high R² on the train set

Residual plots indicate minimal heteroscedasticity or major outliers

📚 Libraries Used
python
pandas, numpy, matplotlib, seaborn, sklearn, pandas_profiling
