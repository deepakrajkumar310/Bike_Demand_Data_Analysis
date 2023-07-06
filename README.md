# Bike_Demand_Data_Analysis
First, we have gone through and understood the data.
Then we imported various libraries using import command. These libraries include NumPy, Pandas, Matplotlib and Seaborn.
Then we loaded the data using pd.read_csv() function.
We then observed the information and summary of the columns using info() and describe() functions.

Later we performed Exploratory Data Analysis (EDA) on all the columns including Numerical and Categorical columns.
Also, some of these columns were explored together.
All the insights were provided against exploration of each column.

Later we did Data Wrangling.
We have checked for duplicate values and found that there are no duplicate rows in the data.
Also the columns have been checked for null values using isnull() function. It is found that there are no null values in the data.
The outliers (i.e., extreme values) have been handled using filtering functions.
The ‘datetime’ column has converted from object to datetime type.
The numerical features have been handled using StandardScaler and MinMaxScaler depending on the skewness of the columns.
