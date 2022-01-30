# Data Preprocessing
## Project description
This is one of my first projects in my journey of Data analysis which deals with Data pre-processing. Data preprocessing is crucial to create a data set which suitable for analysis.
The main goal of this project was to 'odentify factors which impact the customers ability to repay the loan. The 2 variables considered for this analyis were ' marital status' and ' no. of children'. The data already had some customers’ credit worthiness data points. Based on the historical data, a report was created to identify which category of customers were prone to default thereby also helping the bank identify the ability of a potential borrower to repay their loan.

## Languages & Libraries used
- Python
- Pandas
- NLTK (SnowballStemmer)

## Key skills learned
How to handle the following situations in a large dataset in Python:
- Identifying data type
- Missing values (NaN and None)
- Duplicate values
- Erroneous values
- Data categorization

## Keys steps followed

 Following were the steps followed to make the data clean and actionable: 
- The first step was to open ,and read the CSV file and save it as a dataframe
- Next step involved cleaning the data to make it suitable for analysis. 
-analyze the raw data to identify data errors
- strategies used for cleaning data 
    - missing values
    - erroenous values
    - duplicate data
- strategies for analyzing data
    - data type conversion *(for e.g. string <> numbger)*
    - categorizing data
- Based on the historical data , the categories were identified as more likely to default as compared to the other category. 




## Conclusion
A very crucial step in the data analysis is to ensure that the data we are using is correct and does not contain many errors. To increase the quality of data, duplicates are removed, missing values are replaced ,or missing values are removed , erroneous values are either replaced or removed. The ways I used to replace missing values included, grouping them by one parameter and replacing the missing values by mean/medien or mode. After cleaning the data , a simple method of categorization was used in order to group the data into categories. Using the historical data on defaulting of loan, the categories were classified as those which are more likely to default as against the other categories. 