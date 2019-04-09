# DATA ANALYTICS BOOT CAMP - PROJECT 2

## Cryptocurrency Values over Time
### Margaret Oluwatoyin sippiotitiloyeola, Dylan Bruce, and Mirella Mardakis


### Purpose: 
###### The purpose of this project is to display the values per day for the past six year of four popular cryptocurrencies: Bitcoin, Ethereum, Neo, and Iota.

### Extract:
###### We extracted four separate CSV files from Kaggle.com. 

### Transform: 
###### 	We converted the CSV files into Pandas dataframes, deciding to use all the existing columns, as the information is relevant to analyzing value fluctuations over time.
###### When creating table columns in SQL, some column names had to be used as strings, as their names were also existing data types (such as “date”).
###### The date columns in the dataframes had to be converted to the SQL format of YYYY-MM-DD. To do this, we used datetime, strftime and strptime to convert from Mon DD, YYY to YYYY-MM-DD. This function was looped over the “date” column in all dataframes. 

### Load:
###### The data is loaded into a MySQL relational database. This type of database works best for displaying financial trends because it makes joining tables and manipulating numerical data very easy, and this type of information is more efficiently displayed in tables. 


### Data Sources: 
###### Bitcoin: https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory#bitcoin_price.csv
###### Ethereum: https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory#ethereum_price.csv
###### Neo: https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory#neo_price.csv
###### Iota: https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory#iota_price.csv
