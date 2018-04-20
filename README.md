# Python Script to Explore US Bikeshare Data
This Python script is written for Project 2 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore data related to bike share systems for Chicago, New York City, and Washington. It imports data from csv files and compute descriptive statistics from the data. It also takes in users' raw input to create an interactive experience in the terminal to present these statistics.

## How to run the script
You can run the script using a Python integrated development environment (IDE) such as Spyder. To install Spyder, you will need to [download the Anaconda installer](https://www.anaconda.com/download/). This script is written in Python 3, so you will need the Python 3.x version of the installer. After downloading and installing Anaconda, you will find the Spyder IDE by opening Anaconda Navigator.

## Datasets
The datasets used for this script contain bike share data for the first six months of 2017. Some data wrangling has been performed by Udacity's staff before being provided to the students of DAND. Under the permission of Udacity, I have uploaded a copy of the datasets [here](https://drive.google.com/open?id=16FfhNDfAh0DvTIRw9r0plmWZlHPEcBa4). The file sizes are too big to be uploaded on GitHub, so they were uploaded on Google Drive instead. After downloading the datasets, place them in the same folder with this Python script.

The data is provided by [Motivate](https://www.motivateco.com/), which is a bike share system provider for many cities in the United States. The data files for all three cities contain the same six columns:
* Start Time
* End Time
* Trip Duration (in seconds)
* Start Station
* End Station
* User Type (Subscriber or Customer)

The Chicago and New York City files also contain the following two columns:
* Gender
* Birth Year

## Questions explored
The script answers the following questions about the bike share data:
* What is the most popular month for start time?
* What is the most popular day of week (Monday, Tuesday, etc.) for start time?
* What is the most popular hour of day for start time?
* What is the total trip duration and average trip duration?
* What is the most popular start station and most popular end station?
* What is the most popular trip?
* What are the counts of each user type?
* What are the counts of gender?
* What are the earliest (i.e. oldest person), most recent (i.e. youngest person), and most popular birth years?

## Future scopes
In the future, more functions that compute statistics will be added to answer more questions about the data. The possibilities of improving the interactive experience (e.g turning this script into a web app) will also be explored.

## Resources referred to complete this project
Use parse_dates to recognize datetime columns:
* https://stackoverflow.com/questions/21269399/datetime-dtypes-in-pandas-read-csv
* https://stackoverflow.com/questions/17465045/can-pandas-automatically-recognize-dates
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.read_csv.html

Assess datetime series:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
* https://stackoverflow.com/questions/29366572/pandas-how-to-filter-most-frequent-datetime-objects

Filter date:
* https://stackoverflow.com/questions/29370057/select-dataframe-rows-between-two-dates

Check validity of date:
* https://stackoverflow.com/questions/9987818/in-python-how-to-check-if-a-date-is-valid/9987935

Add a day to a date:
* http://www.pressthered.com/adding_dates_and_times_in_python/

Read day of week, month, hour etc.:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.dayofweek.html

Convert seconds to hours, minutes and seconds:
* https://stackoverflow.com/questions/775049/how-to-convert-seconds-to-hours-minutes-and-seconds
* https://docs.python.org/3/library/functions.html#divmod

Convert pandas series or dataframes to string:
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.to_string.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.to_string.html

Concatenate strings of two columns:
* https://stackoverflow.com/questions/19377969/combine-two-columns-of-text-in-dataframe-in-pandas-python
* http://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.str.cat.html#pandas.Series.str.cat

Set column widths:
* https://pandas.pydata.org/pandas-docs/stable/options.html
* https://pandas.pydata.org/pandas-docs/stable/generated/pandas.set_option.html

Other pandas and numpy functions:
* Lessons in the Introduction to Data Analysis section of Udacity's Data Aanalyst Nanodegree (DAND)
