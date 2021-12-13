# Tools-for-Analytics-Group-Project
By Andree and Harish

Authors
-------------------
1. Andree Makahinda (abm2203)
2. Harish Vatsen (hv2228)



Top10.ipynb
-----------------------
In this notebook, we analyzed the top 10 causes of calls to 311 in 10025 area. The steps to do that are as follows.
- Reading the csv files and storing it to a variable called df
- Having a quick look at the df with df.info()
- Checking the first couple of rows of the df with df.head()
- Finding out all the columns in the df with df.columns
- Defining the zipcode (zipcode = 10025)
- Filtering the original df so that it only contains rows equals to the zipcode
- Defining the top 10 causes of the call in the filtered df using groupby function, count() method, loc identifier, and sort_values() method
- Assigning the results to a variable called top10
- Confirming the type of top10 variable where we expected it to be a pandas.Series
- Showing and checking the labels and values of the top10 pandas.Series



Parking.ipynb
-----------------------