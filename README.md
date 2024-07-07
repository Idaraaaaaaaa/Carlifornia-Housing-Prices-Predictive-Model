# Carlifornia-Housing-Prices-Predictive-Model
Problem statement
Accurately predicting house prices is a challenging yet essential task in the real estate industry. Traditional methods often struggle to handle the complexity and variability of real estate data, which includes diverse features such as location, size, number of rooms, and various other factors. This complexity is compounded by issues such as multicollinearity and noise in the data, which can impair the performance of predictive models. Given these challenges, there is a need for an effective approach to preprocess and model real estate data to improve prediction accuracy.

The goal of this project is to develop a robust regression model that can accurately predict house prices by addressing the aforementioned challenges. To achieve this, we trained multiple regression models and selected the best-performing one based on key accuracy metrics. The ultimate goal is to offer a more objective, consistent, and scalable alternative to traditional property valuation methods, thereby improving decision-making processes in the real estate market and benefiting all stakeholders involved in real estate transactions.

Prepare Data
Dataset description

For this project we will be working with California Housing Prices Data (5 new features!) which contains the Median house prices for California districts derived from the 1990 census. The columns are as follows, their names are pretty self-explanatory:
Median House Value: Median house value for households within a block (measured in US Dollars) [$]

Median Income: Median income for households within a block of houses (measured in tens of thousands of US Dollars) [10k$]

Median Age: Median age of a house within a block; a lower number is a newer building [years]

Total Rooms: Total number of rooms within a block

Total Bedrooms: Total number of bedrooms within a block

Population: Total number of people residing within a block

Households: Total number of households, a group of people residing within a home unit, for a block

Latitude: A measure of how far north a house is; a higher value is farther north [°]

Longitude: A measure of how far west a house is; a higher value is farther west [°]

Distance to coast: Distance to the nearest coast point [m]

Distance to Los Angeles: Distance to the centre of Los Angeles [m]

Distance to San Diego: Distance to the centre of San Diego [m]

Distance to San Jose: Distance to the centre of San Jose [m]

Distance to San Francisco: Distance to the centre of San Francisco [m]

Data Preprocessing: 
Target Variable- median_house_value
Features=  Tot_Rooms, Latitude, and Longitude


Model Selection
We use xgb regressor
