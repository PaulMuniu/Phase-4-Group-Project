# Zillow Housing Data Time Series Modeling 🏘️
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/real%20estate%20image.jpg)


### Team Members:

 #### Silvia Gworit
 #### Dennis Mwenda
 #### Myra Kadenge
 #### Paul Muniu
 
 
 ##  Project Overview
This project focuses on time series modeling using Zillow housing data. The primary objective is to understand housing market trends and forecast future values using various time series analysis techniques.

### Table of Contents: 

##### 1.Business Understanding
 
##### 2.Data Understanding

##### 3.Data Preparation

##### 4.Exploratory Data Analysis

##### 5.Modeling

##### 6.Conclusion

##### 7Limitations

##### 8.Recommendations

##### 9.References

### Business Understanding
#### Introduction
This project involves time series modeling using Zillow housing data. The goal is to understand housing market trends and forecast future housing prices.

#### Business Problem
The project aims to provide insights into housing price trends and help stakeholders make informed decisions.

### Objectives
**Analyze historical housing data.

**Develop time series models to forecast future housing prices.

**Evaluate the performance of different time series models.

## Data Understanding

### Summary of the Dataset
The dataset comprises 14,723 rows and 272 columns, mainly in wide format with date columns.

### Data Ispection 
The dataset includes various data types and spans multiple zip codes and time periods.

## Data Preparation 

### Duplicates and Missing Values
Handled duplicates and missing values to ensure data quality.

### Renaming and Conversion
Standardized column names and data types.

### Feature Engineering: Return on Investment (ROI)
Calculated ROI for each zip code to identify top-performing areas.

### Checking for Outliers
Analyzed outliers to determine their impact on the dataset.

### Top 5 Zip Codes with Highest ROI
The top 5 zip codes with the highest ROI were identified and analyzed.

### Top 5 ZipCode Areas with High Growth Rate
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/zipcodes%20with%20high%20growth%20rates.png)

### Resampling
Data was resampled to different time intervals:

 **Monthly Data
 **Quarterly Data
 **Yearly Data
 
# Exploratory Data Analysis

## Univariate Analysis

### Top 10 Most Popular Counties
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/top%20Most%20popular%20countries.png)
Los Angeles is the most popular county with approximately 70,000 zip codes.


### Top 10 Most Popular Cities
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/popular%20cities.png)
New York City, Los Angeles, and Houston are the most popular cities.


#### Average House Prices by State
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/av.%20housing%20prices.png)
Analysis of average house prices across different states.

## Bivariate Analysis

### Top States Based on Average Value
![Genre Rating Relationship](https://github.com/PaulMuniu/Phase-4-Group-Project/blob/main/Images/top%20states%20based%20on%20av.%20value%20over%20years.png)
States like California and others were analyzed based on average housing values.


# Modeling

## Baseline Model  : Simple Moving Average (SMA)
Established a baseline using the Simple Moving Average model.

## ARIMA Modeling
Developed ARIMA models to forecast housing prices.

## AutoARIMA Model
Used AutoARIMA for automatic parameter selection.

## Final Model: Facebook Prophet
Implemented Facebook Prophet for advanced time series forecasting.

## Conclusion
The project provided valuable insights into housing market trends and developed models for future price predictions.

**Baseline Model**  
The Baseline ARIMA model shows excellent predictive performance, with low Mean Squared Error (MSE) for both training and test datasets. The close alignment of actual and predicted values in the graphs highlights its effectiveness in capturing historical trends, making it ideal for minimizing prediction errors.

**Facebook Model**  
The Facebook model is crucial for handling seasonality, particularly evident during the 2008 financial crisis when house prices dropped. It indicates an upward trend in house prices across various zip codes, with distinct growth rates. Notably, prices tend to rise starting in December. This model can be adjusted to adapt to future financial crises and seasonal patterns.

**Top 5 Zip Codes for Investment:**  
7302, 11211, 11215, 11216, and 11222, based on return on investment.

### Recommendations
1.Positive predicted values for the top 5 zip codes suggest promising investment opportunities.

2.Consider the city's unique characteristics, development prospects, and economic growth when making investment decisions.

3.Focus on cities with higher ROI figures, as they indicate efficient investment opportunities for example Houston, Riverdale and NewYork.

4.Consider Diversification: While all the analyzed states exhibit favorable investment opportunities, consider diversifying the investment portfolio across multiple states. This approach can help mitigate risk and capture various market dynamics.

### References
List of references used in the project
1.https://facebook.github.io/prophet/docs/quick_start.html

2.https://github.com/PMEAL/pmdarima

3.https://scikit-learn.org/stable/modules/model_evaluation.html
.
