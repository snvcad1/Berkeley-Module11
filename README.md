## Berkeley-Module11 - Car Price Prediction - What factors make a car more or less expensive

# Overview**
This repository contains the Jupyter Notebook for the Assignment 11.1. This takes Kaggle used car data in vehicles.csv file in the data folder of this repository to build a machine learning application that evaluates if vehicles features like Fuel, Condition, Size, Type, Color etc. can be used to determine used car prices for the Car Dealership and Sales Team. This evaluation will help the Car Dealership with fine tuning their inventory by stocking cars that consumers are interested in.

# Respository Structure
- data : Contains vehicles.csv file which was downloaded -  Kaggle Machine Learning dataset repository
- notebook : Userd Car Price Predition (UsedCarPricePrediction-Final.ipynb)

# Learning Outcome
Objective is to identify key features for used car prices based on the dataset provided so that Car Dealers and their Sales Team can use these key features to understand the cars that they need to have in their inventory to increase sales.The assignment focuses on applying exploratory data analysis, plotting, statistical summarization, and data visualization skills to a machine learning problem and also create the best prediction model to use.

# Data Understanding
The first thing that was apparent -  the provided data was that it was not clean, it had missing values and some of the values were not realistic for used cars, for example, odometer with zero and single digit values; price with zero and single digits values.

# Prerequisites
This project requires the following Python libraries:
 
pandas (for data manipulation)
numpy (for numerical operations)
sklearn(for predictive data analysis)
matplotlib.pyplot (for plotting)
seaborn (for enhanced visualizations)

# Usage Summary
To use the project:

Clone the Repository: Use the command git clone **https://github.com/snvcad1/Berkeley-Module11.git** to clone the repository.
Install Dependencies: Execute pip install -r requirements.txt to install the necessary dependencies.
Open the Jupyter Notebook: Launch the notebook with jupyter notebook notebook.ipynb and run the cells to explore the analysis.

Structure of the repository:
- Berkeley-Module11
   ---car-data-processing.ipynb : First file to process and clean up the data
   ---car-data-visualization.ipynb : Second file to see the visualization of the processed data.
   ---car-price-model.ipynb : Thirs file that runs Linear, Lasso, Random Forst regression model to predict the price.
   ---images : all images are stored here.
   ---data : orginial and final data files are stored in a zip file which needs to be unziped before you run the code.
  
Dependencies
The project requires the following Python packages, which are listed in requirements.txt:
- pandas
- numpy 
- seaborn 
- matplotlib.pyplot 
- tqdm
- sklearn
- sns
- xgboost
- lightgbm
  

