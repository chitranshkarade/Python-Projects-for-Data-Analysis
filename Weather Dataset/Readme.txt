
Weather Dataset-

In this project, we analyzed a weather dataset using the Pandas library in Python. The dataset contained information on various weather parameters such as temperature,
humidity, and visibility, among others. We started by exploring the dataset using various Pandas methods such as head(), describe(), and info(), among others, to gain 
an understanding of the data. We then proceeded to clean the data by removing missing or duplicated values, correcting data types, and renaming columns, among other 
things. This process helped us ensure the accuracy and completeness of the dataset. Overall, the use of Pandas made it easy to explore and clean the data, enabling us 
to extract meaningful insights and perform further analysis.

The commands that we used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.

Exercise - 

Q. 1)  Find all the unique 'Wind Speed' values in the data.
Q. 2) Find the number of times when the 'Weather is exactly Clear'.
Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.
Q. 4) Find out all the Null Values in the data.
Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.
Q. 6) What is the mean 'Visibility' ?
Q. 7) What is the Standard Deviation of 'Pressure'  in this data?
Q. 8) What is the Variance of 'Relative Humidity' in this data ?
Q. 9) Find all instances when 'Snow' was recorded.
Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.
Q. 11) What is the Mean value of each column against each 'Weather Condition ?
Q. 12) What is the Minimum & Maximum value of each column against each 'Weather Condition ?
Q. 13) Show all the Records where Weather Condition is Fog.
Q. 14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
Q. 15) Find all instances when :
	A. 'Weather is Clear' and 'Relative Humidity is greater than 50'
	or
	B. 'Visibility is above 40'
