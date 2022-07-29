# Cleansing-Data
Cleaning data from Superstore Data collection, and generating an CSV file in order to adequate the requisites for SQL parsing


Using Pandas we can read the initial csv file where special characters are found and forbidden by MySQL. 

Using a simple .replace() method we can clean the entire table, in order to store the later result in the db directory.

Example: 
df = df.replace('�',' ', regex=True)

Lastly upload the modified new version of the .CSV file to https://www.convertcsv.com/csv-to-sql.htm so we can convert it to a command for creating the table and adding the file values. 
