
# Insight into Seattle Airbnb listings  

## Table of Contents
- [Overview](#overview)
- [Software Requirements](#software)
- [Summary of files](#deliverables)
- [Results](#summmary)
- [References](#acknowledgments)



<a id='Overview'></a>
## Overview

The project illustrates the cross-industry process for data mining ie. CRISP-DM using Seattle AirBNB dataset. The objective of the analysis and modeling of the dataset is to gain insights on the following -

1. Listings growth over the years in various neighbourhoods of Seattle.
2. Identify neighbourhoods :
    2a. Favoured by the guests.
    2b. Distinct neighbourhoods in terms of pricing and ratings. 
3. What times of the year,do we see availability at best pricings.
4. Features that influence the property pricing.

The process structure for wrangling, modeling and deploying of the results is as below -
    
  * Overview
  * Business Understanding
  * Data Understanding
  * Data Preparation
  * Data Modeling and Evaluation
  * Deployment

<a id='software'></a>
## Software Requirements



This project requires Python 3.x and following Python libraries installed:

    numPy
    pandas
    scikit-learn
    matplotlib
    xgboost
    seaborn
    statsmodels
    calmap

<a id='deliverables'></a>
## Summary of files 

**Data files**

 1. *calendar.csv*      365 days availability schedule for all listings along with pricing.
   
 2. *listings.csv* Main file which holds the listings data of the hosts.

**Jupyter notebook code file for data analyis and modeling**

Analysis of Seattle airbnb listings.ipynb

**Intermittant files from analysis**

abs_listings_final.csv

abs_listings_model.csv

**Analysis Report**

Analysis of Seattle airbnb listings.html

README.md

<a id='summary'></a>
## Results 

Results and insights have been collated as a blog. Objectives addressed from the analysis and modeling -

1. Visualizing the linear relationship between Price vs review related columns and listings_count, we see that medium to low priced listings have garnered higher reviews with mostly high review ratings.
2. Superhosts perform better in all parameters of review rating.
3. Listings growth over the years
4. Concentration of multiple listings in the neighbourhood groups.
5. How are the neighbourhoods doing in terms of listing counts and review rating
6. Price and review scores rating influence on neighbourhood groups
7. Property available for rent for all 365 days /year across neighbourhoods in terms of listings count
8. Availability based on review ratings across neighbourhoods
9. Availability based on review ratings across neighbourhoods
10.Availabilty of property type and their pricing
11. Availabilty and Price across the 4 quarters across neighbourhoods

<a id='acknowledgements'></a>
## References 

https://www.airbnb.co.in

https://www.sv-europe.com/crisp-dm-methodology/#evaluation

https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome

https://xgboost.readthedocs.io/en/latest/python/python_api.html

https://datascience.stackexchange.com/questions/34209/xgboost-quantifying-feature-importances

http://www.grroups.com/blog/an-information-gain-based-feature-ranking-function-for-xgboost

https://datascience.stackexchange.com/questions/12318/how-to-interpret-the-output-of-xgboost-importance

https://www.visitseattle.org/neighborhoods

https://www.neighborhoodscout.com/

https://www.niche.com

https://en.wikipedia.org/wiki/
