# udacity-data-analysis-data-visualization
Udacity - Project 5 - Data Visualization

## About this Project

This project is part of Udacity's Data Analyst Nanodegree. In this project, a [dataset](https://www.lyft.com/bikes/bay-wheels/system-data) containing data about Bay Wheels bike service is wrangled and analyzed to answer questions like: Do user type affects how the bikes are used? Is there any correlation between the distance and duration of the trips? 

## Getting Started

### Why? 

The goal of this analysis is to understand the relationships between distances covered, time spent biking, user type, and periods of the day and any correlations. 

### Main Findings

  - Distance and time are correlated and influenced by the periods of the day.  
  - The user type has a small influence on distance and time. 
  - The periods of the day have a direct influence on distance and time. 
    
Results are displayed in the slides presentation file. These results are focused on explaining the relationship between distance, duration, user type, and period of the day. Some analysis was left out of the final presentation to focus on answering the proposed question. 

### Research during the analysis

[Title and label font size](https://stackoverflow.com/questions/12444716/how-do-i-set-the-figure-title-and-axes-labels-font-size-in-matplotlib)

[nbconvert issues](https://github.com/jupyter/nbconvert/issues/915)

[Calculate distance using lat and lon](https://kite.com/python/answers/how-to-find-the-distance-between-two-lat-long-coordinates-in-python)
    
### Feedback

When presenting the visualizations, some comments were made: 

  - Font and graph size looks small in standard screens.
  - Graphs are not center aligned. 

### Files

Jupyter notebook (bay-wheels.ipynb), where the code is written. 

A slides presentation file is provided with only the main insights and wrangling process of the analysis. 

The data used is contained in 202003-baywheels-tripdata.csv.

### Running the code

To run this project you should have a local server running with Jupyter Notebook installed (you can use [Anaconda](https://www.anaconda.com/distribution/))

The Jupyter notebook is filled with two types of cells, markdown and, code. To run the cells press shift + return and then check the results if there is any to be shown. 

### Built With 

[Python Pandas](https://pandas.pydata.org/) 

[Numpy](https://numpy.org/)

[Matplotlib](https://matplotlib.org/)

## Authors
Eduardo Domingues - [Git](https://github.com/eduardopd)
