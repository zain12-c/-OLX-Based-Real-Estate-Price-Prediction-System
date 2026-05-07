# -OLX-Based-Real-Estate-Price-Prediction-System
A machine learning-based system that predicts real estate prices by scraping and analyzing property listings from OLX, helping buyers and sellers make smarter, data-driven decisions.

Tools & Technologies Used:

BeautifulSoup is used for web scraping OLX property listings. It extracts key property details such as location, size, number of rooms, and price from the HTML structure of OLX pages and converts them into a structured, usable dataset.

Pandas is the primary data manipulation library used throughout the project. It handles loading the scraped dataset, cleaning messy data, handling missing values, transforming columns, and preparing the final structured dataframe for analysis and model training.

NumPy is used for numerical computations and array operations. It supports data preprocessing tasks such as handling outliers, performing mathematical transformations, and preparing numerical features for the machine learning model.

Matplotlib is used for data visualization during the Exploratory Data Analysis (EDA) phase. It generates charts and plots such as histograms, scatter plots, and bar charts to visualize property price distributions and trends across different areas.

Seaborn works alongside Matplotlib to create more advanced and visually appealing statistical plots. It is used to identify correlations between features, visualize heatmaps, and uncover key patterns and factors that affect real estate prices.

Scikit-learn is the core machine learning library used in this project. It provides tools for data splitting, feature scaling, model training, and performance evaluation. It also supports the implementation of the Linear Regression model and metrics like R² score and Mean Absolute Error.

Linear Regression is the machine learning algorithm used to predict property prices. It learns the relationship between property features such as location, size, and number of rooms and their corresponding prices, then uses that knowledge to predict prices for new listings.

Flask serves as the backend web framework. It connects the trained machine learning model with the frontend interface, handles user input through API routes, processes the data, and returns the predicted price as a response in real time.

HTML/CSS is used to build a simple and clean frontend interface where users can enter property details such as location, size, and number of rooms and instantly receive a predicted price powered by the ML model in the backend.

Key Features:

 OLX Web Scraping — Automatically extracts real property listings using BeautifulSoup
 Data Preprocessing — Cleans raw data, handles missing values and outliers
 Exploratory Data Analysis — Visualizes trends and patterns using Matplotlib and Seaborn
 ML Price Prediction — Predicts property prices using a trained Linear Regression model
 Real-Time Results — Flask backend delivers instant predictions to the frontend
 Simple UI — Clean HTML interface for easy property detail input and price output
 Feature-Based Analysis — Considers location, size, rooms and more for accurate predictions


 Model Performance
 
R² Score — Measures how well the model explains price variance

Mean Absolute Error (MAE) — Average difference between predicted and actual prices

Mean Squared Error (MSE) — Penalizes larger prediction errors for better accuracy
