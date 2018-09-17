 # 911 Calls analysis


For this capstone project we will be analyzing some 911 call data from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The data contains the following fields:

* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)


## Basic Tasks

** What are the top 5 zipcodes for 911 calls? **
** What are the top 5 townships (twp) for 911 calls? **
** Take a look at the 'title' column, how many unique title codes are there? **
** creat a new feature create a new column called "Reason" that contains this string value. **
** What is the most common Reason for a 911 call based off of this new column? **
** Now let us begin to focus on time information. What is the data type of the objects in the timeStamp column? **
** Now use seaborn to create a countplot of the Day of Week column with the hue based off of the Reason column. **
** Now do the same for Month: **
** Did you notice something strange about the Plot? **
** Now create a simple plot off of the dataframe indicating the count of calls per month. **
** Now see if you can use seaborn's lmplot() to create a linear fit on the number of calls per month. Keep in mind you may need to reset the index to a column. **
**Create a new column called 'Date' that contains the date from the timeStamp column. You'll need to use apply along with the .date() method. ** 
** Now groupby this Date column with the count() aggregate and create a plot of counts of 911 calls.**
** Now recreate this plot but create 3 separate plots with each plot representing a Reason for the 911 call**
** Now let's move on to creating  heatmaps with seaborn and our data. We'll first need to restructure the dataframe so that the columns become the Hours and the Index becomes the Day of the Week. There are lots of ways to do this, but I would recommend trying to combine groupby with an [unstack](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.unstack.html) method.**
** Now create a HeatMap using this new DataFrame. **
** Now create a clustermap using this DataFrame. **
** Now repeat these same plots and operations, for a DataFrame that shows the Month as the column. **
**Continue exploring the Data however you see fit!**





   
