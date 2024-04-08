# PyBer_Analysis
### Leslie Debassige 


## Overview of Project
The challenge is to create a written analysis with three key deliverables as follows; 

Here is the list of deliverables for the analysis of the PyBer Analysis: 

- Deliverable 1: A ride-sharing summary DataFrame by city type
- Deliverable 2: A multiple-line chart of total fares for each city type
- Deliverable 3: A written report for the PyBer analysis (README.md)

The tools that will be used are Anaconda and the following packages: Python 3.7, a web-based application Jupyter Notebook, Pandas library. In addtion ensuring a working copy of the coding environment; development / virtual environment is posting to GitHub repository for the team to review work if required.  

The datasets that we will be using for the Challenge are three csv files called City_data.csv, PyBer_ride_Data.csv. and Ride_data.csv.

We are building skills in statistical analysis using Matplotlib to create line charts, bar charts, scatter plots, bubble charts, pie charts, and box-and-whisker plots, and make them visually compelling and informative by adding titles, axes labels, legends, and custom colors. You'll also be introduced to SciPy, a statistical Python package, and NumPy, a fundamental package for scientific computing in Python.

Some key features we learned are 

* Creating line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib.
* Adding and modify features of Matplotlib charts.
* Adding error bars to line and bar charts.
* Determiniung mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Purpose

The purpose is to complete an analysis with the following tasks for Omar utilizing tools and data. 

Deliverable 1: A ride-sharing summary DataFrame by city type
==============================================
We will be utilizing the groupby() function, count() and sum() methond, format numbers and strings.

In order to calculate the following as shown in Figure 1:
- The total number of rides for each city type is retrieved. 
- The total number of drivers for each city type is retrieved. 
​- The sum of the fares for each city type is retrieved. 
​- The average fare per ride for each city type is calculated. 
- The average fare per driver for each city type is calculated. 
- A PyBer summary DataFrame is created. 
- The PyBer summary DataFrame is formatted as shown in the example. 

### Figure 1
![A ride-sharing summary DataFrame by city type](https://github.com/735713038455163/PyBer_Analysis/blob/main/Resources/A%20ride-sharing%20summary%20DataFrame%20by%20city%20type.PNG)

Deliverable 2: A multiple-line chart of total fares for each city type
=======================================================================
We will be creating a line chart using the object-oriented interface method, Annotate charts, Graph a Pandas DataFrame, again using the groupby() function, and sum() method.

In order to calculate the following as shown in Figure 2:

- A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
![groupby](https://github.com/735713038455163/PyBer_Analysis/blob/main/Resources/groupby.PNG)

- A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 
![pivot](https://github.com/735713038455163/PyBer_Analysis/blob/main/Resources/pivot.PNG)

- A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-28. 
![loc](https://github.com/735713038455163/PyBer_Analysis/blob/main/Resources/loc.PNG)

- A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
![resample](https://github.com/735713038455163/PyBer_Analysis/blob/main/Resources/resample.PNG)

- An annotated chart showing the total fares by city type is created and saved to the "analysis" folder as shown in Figure# 2

### Figure 2
![PyBer_fare_summary](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)


## Analysis and Challenges


Three business recommendations to Omar the CEO for addressing any disparities among the city types are as follows:

1. ![Fig1](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig1.png)
Note: Circle size correlates with driver count per city. Urban cities have the highest driver count and total number of rides. Conversely, rural cities with the lowest number of rides and smallest driver count have the highest fares. Omar should consider the number of driver per fare. 
![Fig4](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig4.png)Omar should consider having Urban Drivers work in the Rural and Suburban areas becuase there are 1.48 drivers to one ride. 

2. ![Fig3](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig3.png) There are less fares going to rural areas but they have higher fares. 
![Fig2](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig2.png) The desitation may be to the airport as an example. 
Omar should look into the distance that may be contributing to the larger fare in Rural areas versus the lower fare in Urban cites. It would be interesting to know if the fares included tips or not.

3. Perhaps another consideration is that the company is not making alot of money in Rual area; only 5.3% make up the toal rides in Rural area. Might not be enough to sustain business there. 
![Fig5](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig5.png)
![Fig6](https://github.com/735713038455163/PyBer_Analysis/blob/main/Analysis/Fig6.png)


