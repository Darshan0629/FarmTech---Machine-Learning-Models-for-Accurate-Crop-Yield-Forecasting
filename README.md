# FarmTech---Machine-Learning-Models-for-Accurate-Crop-Yield-Forecasting

Project Overview
This project aims to predict crop yields using historical agricultural data from 71 countries, covering 10 different crops from the years 1990 to 2013. The model incorporates multiple environmental and agricultural factors, such as area, yield (hg/ha), average rainfall, pesticide usage, and average temperature. By employing advanced machine learning algorithms and regression models, we forecast future yields, offering valuable insights for optimizing agricultural productivity and addressing global food security.

Data Description
The dataset used in this project includes the following features:

Area: Cultivated area (in hectares)
Item: Crop type (10 different crops)
Year: Year of the record (1990–2013)
hg/ha_yield: Crop yield in hectograms per hectare
average_rain_fall_mm_per_year: Annual average rainfall (in millimeters)
pesticides_tonnes: Amount of pesticides used (in tonnes)
avg_temp: Average annual temperature (in Celsius)
Algorithms Used
We implemented several machine learning algorithms to predict crop yields and compared their performance based on accuracy and Mean Squared Error (MSE):

Linear Regression:

Accuracy: 7.37%
MSE: 6.29 billion
Random Forest:

Accuracy: 98.56%
MSE: 97.65 million
K-Nearest Neighbors (KNN):

Accuracy: 28.82%
MSE: 4.83 billion
Decision Tree:

Accuracy: 97.61%
MSE: 161.89 million
Artificial Neural Network (ANN):

Accuracy: 16.48%
MSE: 5.67 billion
XGBoost:

Accuracy: 97.43%
MSE: 161.89 million
Gradient Boosting:

Accuracy: 83.11%
MSE: 161.89 million
Interactive Power BI Dashboard
We developed an interactive Power BI dashboard to visualize the data trends and patterns. This tool helps stakeholders explore the relationships between variables like average temperature, rainfall, pesticide use, and crop yield across different regions and time periods. The dashboard serves as a decision-making aid, enabling insights into global agricultural practices.

Installation & Requirements
Libraries and Dependencies:
Python 3.x
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Seaborn
TensorFlow (for ANN model)
Power BI (for dashboard visualization)
