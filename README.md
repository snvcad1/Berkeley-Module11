## Berkeley-Module11 - Car Price Prediction - What factors make a car more or less expensive

# Overview**
This repository contains the Jupyter Notebook for the Assignment 11.1. The Kaggle used car data is vehicles.csv file in the data folder of this repository was used to build a machine learning application that evaluates if vehicles features like Fuel, Condition, Size, Type, Color etc. can be used to determine used car prices for the Car Dealership and Sales Team. This evaluation will help the Car Dealership with fine tuning their inventory by stocking cars that consumers are interested in.

# Learning Outcome
Objective is to identify key features for used car prices based on the dataset provided so that Car Dealers and their Sales Team can use these key features to understand the cars that they need to have in their inventory to increase sales.The assignment focuses on applying exploratory data analysis, plotting, statistical summarization, and data visualization skills to a machine learning problem and also create the best prediction model to use.

# Data Understanding
The first thing that was apparent -  the provided data was not clean. It has missing values and some of the values were not realistic for used cars, for example, price and odometer with zero as the values. The columns (id, VIN, state ) was dropped as it was not critical for the modeling purpose. All the missing values was addressed through imputer method. Numerical values of year and odometer values with 0 was addressed using IterativeImputer method. Empty Categorical values were addressed and removed all the outliers. The final dataset was saved as "vehicles-phase2.csv" file. 

# Data Visualization
The following are some of the sample data visualization chart that was created for the analysis.
![image](https://github.com/user-attachments/assets/4e91e060-8a0b-4bae-8db4-5af3cca39569)
![image](https://github.com/user-attachments/assets/d25c968a-5e9d-41fb-8dc2-8dee0aad8406)
![image](https://github.com/user-attachments/assets/e4ee467a-8eba-4a53-84c6-d879e106c6cb)


# Final Report
Based on the final model, it was determined that Random Regression Model was the best model to predict the price. Based on the 3 models ( Linear, Lasso, Random Forest) that was used, it shows that Random Forest prediction model is the best fit. The key features are year, odometer, cylinders, model, fuel that are importan features that should be considered
![image](https://github.com/user-attachments/assets/e6f1c130-946f-4e29-a504-4da7865be33c)

The key features that are important for price predictions are shown in the below chart.
![image](https://github.com/user-attachments/assets/2797554d-b8ab-4a7a-bfb2-2db0cf370d66)

# Usage Summary
To use the project:

Clone the Repository: Use the command git clone **https://github.com/snvcad1/Berkeley-Module11.git** to clone the repository.
Install Dependencies: Execute pip install -r requirements.txt to install the necessary dependencies.
Open the Jupyter Notebook: Launch the notebook with jupyter notebook notebook.ipynb and run the cells to explore the analysis.

**Structure of the repository:**

- Berkeley-Module11
  - car-data-processing.ipynb : First file to process and clean up the data
  - car-data-visualization.ipynb : Second file to see the visualization of the processed data.
  - car-price-model.ipynb : Third file that runs Linear, Lasso, Random Forst regression model to predict the price.
  - images : all images are stored here.
  - data : orginial and final data files are stored in a zip file which needs to be unziped before you run the code.
  
**Dependencies**
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
  

