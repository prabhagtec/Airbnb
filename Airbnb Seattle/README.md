
### Table of Content

1. [Introduction](#introduction)
2. [Project Motivation](#motivation)
3. [Code Descriptions](#files)
4. [CRISP-DM](#crisp-dm)
5. [Conclusion](#results)

## Introduction <a name="introduction"></a>

I have taken calendar and listing data set from Seattle AirBNB Data to find how price been evaluated 

## Project Motivation<a name="motivation"></a>


1. How do the different property types relate to price?
2. Which is the Costliest month??
3. Does 'review_scores_cleanliness' impact the price?



## Code Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is self exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final conclusion.

## CRISP-DM <a name="crisp-dm"></a>

    # Business Understanding: 
   I use Seattle AirBnB homes data to analyse booking prices against various categories to answer below three questions:
        1. How do the different property types relate to price?
        2. Which is the Costliest month??
        3. Does 'review_scores_cleanliness' impact the price?
    
    # Data Understanding:    
   The data set have 3000+ listing details with 92 columns of data. There are calendar and review data available for analysis too. 
    
    # Prepare Data: 
   Necessary fields are modified by removing NaN values or filling with mean value. Field such as Price was converted from object to float   to perform basic operation by removing $ symbol and filling NaN vaule with mean. 
   
    # Analysis:
   All above three questions are analysised by Phython program as available in this repository.
   
    # Visualisation:
   Drawn visualisation for each question and presented in blog and coding.
   
    # Findings:
   1. Average price was caluculated against different property types would be helpful for future bookings
   2. July is the Costliest month
   3. No, Review score for cleanliness doesn't impact the price.
   

## Conclusion<a name="results"></a>

The detail findings of the code can be found at the post available [here](https://medium.com/@prabhagtec/what-determines-the-price-of-airbnb-accommodation-in-seattle-f5738305e591).



