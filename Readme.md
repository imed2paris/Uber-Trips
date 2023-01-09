# Uber trips


## Topic

* The aim of this project is to see how powerful clustering methods are for exploring data.
* One use is to identify groups among a large number of locations.
* We will analyse data provided by Uber on the location of pick-ups in New York City over one month.


## Objective

* We want to make recommendations on the best places to pick up a customer quickly.
* Machine Learning offers several algorithms to help build homogeneous clusters.
* Depending on the day of the week and the time of day, we will be able to identify the areas where it is best for a VTC driver to position himself in order to start a journey in a short time.


## Issues 

* Before applying any clustering method, determining the optimal number of clusters is a necessary step that should not be taken lightly.
* Obviously, it is important to visualise the clusters on a map so that we can have a global view of things: we need to think about the simplest tool to draw a map without effort.
* It might be interesting to see if there is a difference between the main clustering algorithms (K-Means, DBSCAN, OPTICS).
* During the data preparation phase, it is necessary to convert the latitude/longitude features so that they can be read by the mapping tool.


## Technologies

* I use the usual python packages for data analysis to solve the problem:
    * Pandas for data wrangling, 
    * Seaborn and Matplotlib for data visualization, 
    * Scikit-learn for modeling.
* I use Bokeh to build maps easily.