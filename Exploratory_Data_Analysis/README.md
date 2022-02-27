# Exploratory Data Analysis

This is my project on Exploratory Data Analysis project. To make the data suitable for analysis, apart from checking the quality of th data, additional iterations of preprocessing might be necessary.
Purpose of EDA is to identify outliers, evaluate and modify the structure of data. Analyse categorical data. Look for relationships and patterns in data. Visualise certain parameters. Summarize and draw high level conclusions for the data

# Tools used
1. Tools for building graphs, such as hist(), boxplot(), and plot()
2. Summarize data with the pivot_table() and describe() methods
3. Slice data 
4. Combine tables with the join() method and review the merge() method

# Project description

This project involved analysing advertisement data for vehicles published on a website everyday. The data fields included the following fields like price, model_year, model , condition, technical specifications like cylinders, fuel type , transmission, whether the vehicle has 4-wheel drive, other parameters like mileage, paint colour, date the ad was posted, number of days the ad was listed on the website. Purpose of the project which of the above mentioned factors influence the price of the vehicle. 

# Assumptions
For this project, assumption made was the categories must have at least 50 ads; otherwise, their parameters won't be valid for analysis.

# Conclusion
After removing the outliers, visualising the patterns and studying the correaltion it was identified that 

1. The corelation between the price and age was negative , while with the other parameters, mileage, number of cylinders and condition it was positive.
2. SUV and Truck have the highest number of ads. There appears to be no strong corelation between the price and the number of ads. However there is weak positive corelation. The more expensive the car , more are number of the advertisements placed on the website. 
3. Of the 13 different types of vehicles listed on the website, SUV and trucks were identified as the vehicles of interest. Categorical and quantitative variables were studied for these 2 vehicle type.
4. The price of the car seems to be impacted by the colour of the car. 
5. Some obvious correlations were observed. There is a positive corelation between mileage and condition with price whereas for age the corelation is negative. Between automatic and manual transmission, it is observed that manual cars have fewer outliers than automatic cars, implying that the prices of automatic cars are skewed. There are some cars which are way higher priced than the average price. Indicating that the prices are not uniform for automatic transmission as is the case for manual cars. More or less most of the cars with manual transmission fall under a fixed range.
6. Lastly the higher the cost of the car, the longer the duration of the ad on the website  
7. The typical lifetime of an advertisement extended upto 50 days.

# Recommendations

Typically for a car to be sold through this website , the ad should be placed for a minimum of 20 days. Also the more expensive the car the ad needs to listed for longer. To maximise the chances for a car to be sold through thid website the seller must keep the advertisement on the website for a minimum upto 50 days. Typically more expensive cars need longer to be sold. So it would be recommended to keep the advetisement for more days on the website to maximise the chances of the car to be sold. 
