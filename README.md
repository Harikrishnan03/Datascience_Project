Flight Price Prediction:

Welcome to the Flight Price Prediction project! This project uses machine learning models to predict flight ticket prices and analyse key pricing trends based on factors like flight class, stops, and time of travel.

About the Project:
The goal of this project is to:
  1.	Predict flight ticket prices using models like Linear Regression, Random Forest, and K-Nearest Neighbors.
  2.	Understand the factors that influence ticket prices (e.g., flight class, duration, number of stops).
  3.	Provide insights for airlines and travellers to optimize pricing and booking strategies.

How to Get Started:

1. Requirements:
  To run this project, you need:

    •	Python 3.7 or higher
   
    •	Libraries: pandas, numpy, scikit-learn, matplotlib, and seaborn

  Install the required libraries by running:

    •	pip install pandas numpy scikit-learn matplotlib seaborn

2. Running the Code:

  •	Clone the Repository:
  
  Download the project files from GitHub:
  
    o	git clone https://github.com/Harikrishnan03/Datascience_Project.git
    
    o	cd Datascience_Project
   
  •	Run the Jupyter Notebook:
  
Open the notebook file Flight_Price_Prediction.ipynb in Jupyter Notebook or any Python IDE:
  
  o	jupyter notebook Flight_Price_Prediction.ipynb
    
•	Load the Data:

  Make sure the datasets business.csv and economy.csv are in the same directory as the notebook.
    
•	Execute the Code:
  
  Run the notebook cells sequentially to see the analysis and predictions.
    
Features:

•	Data Pre-processing:
    
  o	Combines business and economy flight data.
  
  o	Cleans data by removing duplicates and handling missing values.
    
•	Feature Engineering:

  o	Calculates flight duration.
    
  o	Categorizes departure/arrival times into parts of the day.
    
•	Visualizations:
  
  o	Distribution of ticket prices.
  
  o	Price trends by day of the week, weekends, and flight class.
    
•	Machine Learning Models:

  o	Linear Regression
  
  o	Random Forest Regressor
  
  o	K-Nearest Neighbors (KNN)
    
•	Hyperparameter Tuning:
  
  o	Optimizes Random Forest and KNN models for better predictions.
  
•	Performance Metrics:

  o	Evaluates models using R² and RMSE.
    
Project Outputs:

1.	Graphs and Trends:
   
  o	Ticket price distribution and trends.
  
  o	Comparisons of business vs. economy class prices.
  
  o	Learning curves for model evaluation.

2.	Model Performance:
   
  o	R² scores and RMSE for each model.
  
  o	Insights into the best-performing model (KNN).

Why This Project is Useful:

•	For Airlines:
  
  o	Helps optimize dynamic pricing strategies.
  
  o	Identifies key pricing trends for different customer groups.
  
•	For Travelers:
  
  o	Suggests the best times to book flights.
  
  o	Highlights the impact of stops, duration, and flight class on pricing.

File Structure:

  Datascience_Project/
  
  ├── Flight_Price_Prediction.ipynb   # Main Jupyter Notebook
  
  ├── business.csv                    # Business-class flight data
  
  ├── economy.csv                     # Economy-class flight data
  
  └── README.md                       # User guide
 
Contact:

Have questions or feedback? Feel free to reach out or raise an issue in the repository:
[https://github.com/Harikrishnan03/Datascience_Project](url)

