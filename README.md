# assignment-for-Lognormal-Analytics
tasks that should be done
Complete the tasks mentioned in each section below with relevant code and execute them to reflect the desired output
Load the Data in the file - "assignment_python.csv" given to you as a .csv using Pandas
Understand the data using the columns given (metadata descriptions below)
Calculate the time period in days for which the customer was active (days from first deposit date) and enter the value in a new column titled 'Customer Lifetime' & what is the lifetime in days for customer ID - 5371454
Find the city & country with the highest number of unique customers
Find the unique count of players in each country (in descending order) & specify the number of unique players from the city - Kayseri
Which city gives the third highest average first_deposit_amount and what is the average amount?
Plot a graph showing the city and the descending unique count of the unique customers (upto the top 40 cities by the unique count) and make a large plot (clearly visible) and make sure the title and labels are clearly visible.
Plot the conversion for each month of the data (Conversion % = No. of unique First Deposits in the month / No. of unique Registrations in the month) Here, the conversion percentage should be reflected in red, and the labels in the X-axis should be year & month out of the Deposit Dates.
What was the conversion rate in June 2022, limit the answer to 2 decimal places. (in %)
Make a copy of the original data in the file assignment_python as a pandas dataframe called 'df_ft' and generate the following columns:
week of day column from the deposit date column
descriptive statistics of the table
make a column with the first_deposit_amounts binned in bins of 500 and reflected against every customer ID (for example, someone with a first deposit amount of 880 should reflect in the binning column as '500-1000'.
Find a 7 days moving average of number of registrations. (calculating an average of the T-7 days for every week's total registrations)
Descriptions:

IDCUSTOMER = Unique Identifier for a customer

GENDER, CITY, COUNTRY = Self Explanatory

FIRST DEPOSIT AMOUNT = Customer's first deposit amount

REGISTRATION DATE = The date of registration of the customer

DEPOSIT DATE = The date of the first deposit made by the registered customer
