# Pymaceuticals-Inc (Matplotlib) 

## Overview

* First checked the data for any mouse ID with duplicate time points and removed all data associated with that mouse ID.

* Used the cleaned data to generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas' `DataFrame.plot()` and Matplotlib's `pyplot` that outllined the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

* Also created a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that depicts the distribution of mice by gender.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted potential outliers in the plot by changing their color and style.
