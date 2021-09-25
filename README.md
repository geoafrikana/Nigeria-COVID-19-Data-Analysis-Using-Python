# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project

Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus, and it has affected major parts of the world. Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its first case on 27th February 2020.

Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.

In this project, I employed data science & analytics skills to collect data, explore the data, perform analysis, create visualizations, and generate insights.

# Project Steps

I took the following steps in analyzing the recorded data:

## Load Datasets

1. I scraped data from the web and created Pandas DataFrames from them.
2. I imported external datasets from Comma Separated Values (CSV) as Pandas DataFrames.
3. I added the scraped and imported dataframes into a dictionary object for easy indexing.

## Data Cleaning and Exploration

Here I familiarized myself with the data and tried to find useful insights by:

1. inspecting the top five (5) rows of each dataframe.
2. using the Pandas DataFrame info() method to view the number of rows, columns, names of columns and datatype of each column in each of the imported dataframes.
3. casting some columns into a lower bit size to save memory.
4. extracting the Nigeria row from the global data.
5. melting the Nigeria row from wide data to long data
5. casting date into the correct Pandas DateTime datatype

## Visualization and Communication

Visualization helps the data scientist get more familiar with the data as well as help communicate findings to stakeholders and decision makers. 

I used various types of charts to visualize the loaded dataframe including; line graphs and different forms of bar charts.

1. I used a barplot to visualize the top ten laboratory confirmed cases.
2. I generate a barplot that shows the Top 10 states in terms of Discharged Covid cases.
3. I generated a plot to show the top 10 Death cases
4. I used lineplots to show the trend of Confirmed, Recovery, Death cases in Nigeria.
5. I used a grouped bar chart to make inference on the effect of Covid-19 on the GDP of Nigeria in 2020.
