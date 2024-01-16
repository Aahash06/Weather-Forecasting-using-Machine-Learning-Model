# Weather Forecasting using Machine Learning Model

## Project Overview

This project aims to predict temperature using various machine learning algorithms, including Linear Regression, Random Forest Regression, Gradient Boosting Regression, and Decision Tree Regression. The prediction is based on multiple factors such as maximum temperature, minimum temperature, cloud cover, humidity, sun hours in a day, precipitation, pressure, and wind speed.

## Use of Algorithms

Different machine learning algorithms are employed for temperature prediction, where datasets are utilized for calculations and analysis. The data is split into training (80%) and testing (20%) sets. For instance, to predict the temperature of Nagpur, India, 8 years of data are used for training, and 2 years are used as a test dataset. This project leverages algorithms like Linear Regression, Decision Tree Regression, Random Forest Regression, and Gradient Boosting Regression for accurate and predictive weather forecasting.

## Methodology

### Dataset

The dataset used in this project is sourced from Kaggle, titled "Historical Weather Data for Indian Cities." Specifically, the data for "Nagpur City" is utilized. The dataset spans from 01-01-2009 to 01-01-2020, containing hourly weather data for more than 10 years. The data extraction was performed using the worldweatheronline.com API and the wwo_hist package. It is important to note that the accuracy of the data cannot be guaranteed.

### Data Exploration and Visualization

The project includes the exploration and visualization of the historical weather dataset for Nagpur City. Plots are generated for each factor over the course of 10 years, providing insights into trends and variations. Additionally, individual plots for each factor are created for a specific year.

### Regression Models

The focus of the project is on temperature prediction for Nagpur City. Various machine learning algorithms and regression models are applied to the historical weather dataset. The following regressions are implemented:

- **Multiple Linear Regression**
- **Decision Tree Regression**
- **Random Forest Regression**
- **Gradient Boosting Regression**

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Weather-Forecasting-ML.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks or Python scripts for each regression model.

Acknowledgements
Kaggle for providing the "Historical Weather Data for Indian Cities" dataset.
worldweatheronline.com API for data extraction.
