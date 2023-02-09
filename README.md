# Final Project for UNCC Data Analytics Bootcamp

# Overview:

Our client, Secret Jones is looking to relocate somewhere in the United States with their family. They have been living abroad for
a long time and are ready to move back to the States. They would like a city that will not only provide a strong job and housing market, but a safe
environment for their family. They have been looking to relocate to either Atlanta, Chicago, or Charlotte as their research shows that
the job and real estate market is booming. However, before deciding on their relocation, they are very 
interested in the violent crime data in those areas. How dangerous a place is will be a huge factor for them as their utmost concern is 
the safety of their family.

Secret Jones has already received an analysis of crime data for Atlanta and Chicago and has asked our company to perform a similar analysis for Charlotte,
NC. 

We have been tasked with analyzing the type of crimes occuring in Charlotte, how often a crime occurs, and which 
area of Charlotte tends to see the most crime. 

Once they see the analysis of the overall crime data in the different areas of Charlotte, they would like for us to predict what type
of crime is most likely to occur in the various parts of Charlotte. Where they come from, assault and burglary are very common and they want to
steer far away from that.

We have pulled data from several sources to analyze the where and the type of crime in the Charlotte area. Data
has come from the Charlotte Mecklenburg Police Department and the FBI's National Incident-Based Reporting System. 

Dataset:
Violent_Crime (CMPD Data portal)
CMPD_Incidents

(Google Drive for CSV downloads as they are too big for Github)[https://drive.google.com/drive/folders/1DmRuIMXm8oksUcNZeLepODC1HEzg_G38?usp=sharing]

Programs used:
Python for data cleaning and analysis

Tableau for visualization.


Steps:

- Clean and Analyze data with Python
	- Convert date column to a usable date/time format 
	- Clean the dataset (remove nulls)
	- Ensure correct data types
- Data Visualization
	- Heat map of crime data
	- Chart showing crime data over the years
	- Charlotte compared to the United States as Whole
	- Charlotte compared to Atlanta and Chicago
- Machine Learning
	- Probability of ... 
		

# RESULTS

**Show crime stats for Atlanta and Chicago and then show crime stats for Charlotte**


The machine learning model shows: 
(
-Probability of a violent crime occuring in a specific zipcode/neighborhood area.
-Machine Learning: Predicting which month has the highest liklihood of violent crime.
-Could combine the crime that is labeled violent and the crime that is not considered violent - and then 
predict the 'type' of crime that could occur in a specific neighborhood)
See a detailed dashboard here: 
)

# SUMMARY
Based on our analysis, we feel that Charlotte would be a better/worse option for XY Jones.

# Team

Ryan Marshall is going to develope the machine learning and will develop a linear regression model.

Kimberly Cavazos is our team lead visual design and will utlize the Tableau to give visual context to the data and our results of our test.

Fiston Rugwiro is our team lead python and ETL responsible for getting us the data cleaned in otder to test.

Brenton Ervin create data tables and oversee all documents for accuracy.

# Liunear Regression Model

The reason we are using a regression model is to predict the frequency of violent crimes in Charlotte. A linear regressing model is used to predict a continous variable, which in our case is crime. Utilizing the data from the CMPD database we can break the data into months and then use previos data to predict violent crimes frequency and how much it will increase or decrease given a certain month. What we are hoping is to see strong correlations in th data that will help determine how dangerous Charlotte is; by determining the frequency of crimes with our model.



***Previous Readme contents***
- The selected topic and the reasoning for that selection (20 points)
- A description of the data (20 points)
- The questions that the team plans to answer with the project (20 points)

*Location of data (link to google drive)


[CMPD Data Portal](https://data.charlottenc.gov/search?collection=Dataset)

This portal has a dataset called "CMPD Violent Crime."
- It contains the year and type of crime committed. It does not specifically list the location but does provide an "NPA" code per crime. That stands for "neighborhood profile area." 
- The NPA code can be linked with other datasets and shapefiles to get locations across the CMPD area. (Trying to find how to link them).
- There are other crime datasets available (such as crimes that are ***not*** considered "violent")

Ideas:

- Machine Learning: Probability of a violent crime occuring in a specific zipcode/neighborhood area.
- Machine Learning: Predicting which month has the highest liklihood of violent crime.
- Could combine the crime that is labeled violent and the crime that is not considered violent - and then predict the 'type' of crime that could occur in a specific neighborhood

Just my thoughts - thought I would go ahead and jot them here. 

**Hypothesis
   
   Our group decided to use violent crimes in Charlotte data sourced from City Of Charlotte? database:https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/explore?location=35.261391%2C-80.809400%2C10.50&showTable=true

**Question
   
    What is the probability that you would experience a violent crime in charlotte?
    
 **Test
   
    We are thinking of using a linear regression model to predict the likely hood that a violent crime will happen to you in charlotte using the charlotte database we will should be able to determine in what area/zipcode where these crimes happen.
    
  **Results Usefullness
  
   We believe that our predictive test will be useful to real estate developers, locals, tourism, and business locations. This data could be used to prevent civilians and businesses from making costly errors that could lead to huge losses finacial and personal. In addition this analysis could be used to make the city safer by identifying which areas see the most conflict so city administration can make the necessary changes to decrease criminal activity.
   
