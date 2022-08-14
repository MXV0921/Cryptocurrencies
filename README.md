# Cryptocurrencies
In this project we expanded our level of understanding of Machine Learning Models. 

# Preparing the Data
We prepared our raw data about crypto-currency for Principal Component Analysis(PCA).  After importing and analyzing our dataset, we dropped null values to clean the DataFrame ensuring that our learning model is working with clean data.

## Get Dummies Feature
Pandas has a function called "get_dummies" which will convert column data into binary classification of '0' or '1' which is needed for more complex algorithms used later in the project.

## Scaling Data
Our dataset is scaled using the "StandardScaler" function. This function helps to gain consistency across a large random dataset and gives more functionality for comparison across multiple categories.

## Reducing Dimensions
When comparing large datasets, we can declare PCAs with our scaled data.  This will look for consistencies across the data and group the data based on the number of components we declare when fitting the data.

