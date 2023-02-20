![Charlotte Image](https://github.com/Kcav18/Final_Project/blob/main/Images/Charlotte_uptown.jpeg)

# Final Project for UNCC Data Analytics Bootcamp

# OVERVIEW:

Our client, Secret Jones is looking to relocate somewhere in the United States with their family. They have been living abroad for
a long time and are ready to move back to the States. They would like a city that will not only provide a strong job and housing market, but a safe
environment for their family. They have been looking to relocate to either Atlanta, Chicago, or Charlotte as their research shows that
the job and real estate market is booming. However, before deciding on their relocation, they are very 
interested in the violent crime data in those areas. How dangerous a place is will be a huge factor for them as their utmost concern is 
the safety of their family.

Secret Jones has already received an analysis of crime data for Atlanta and Chicago and has asked our Charlotte based company to perform a similar analysis for Charlotte, NC. 

We have been tasked with analyzing the type of crimes occuring in Charlotte, how often a crime occurs, and which 
area of Charlotte tends to see the most crime. 

Once they see the analysis of the overall crime data in the different areas of Charlotte, they would like for us to predict what type
of crime is most likely to occur in the various parts of Charlotte. Where they come from, assault and burglary are very common and they want to
steer far away from that.

We have pulled data from several sources to analyze the where and the type of crime in the Charlotte area. Data
has come from the Charlotte Mecklenburg Police Department and the FBI's National Incident-Based Reporting System. 

Dataset:
[CMPD Data portal](https://data.charlottenc.gov/search?collection=Dataset)

- CMPD_Violent Crime
- CMPD_Incidents
- [Google Drive Link for CSV Files](https://drive.google.com/drive/folders/1DmRuIMXm8oksUcNZeLepODC1HEzg_G38?usp=sharing)
- Google link for SQL Setup https://drive.google.com/drive/folders/1jZD2btjfZurDcPYr0KOe385xIo9teloL
*Please note that the data files are too large to be uploaded to our repository so we have included a link to a Google drive folder that houses those files.*

Programs used:
Python for data cleaning and analysis

Tableau for visualization.

Steps:

- Clean and Analyze data with Python
	- Convert date column to a usable date/time format 
	- Clean the dataset (remove nulls)
	- Ensure correct data types
- Data Visualization

- Machine Learning
	- We are using a linear regression model to predict the frequency of violent crimes occuring per month. 

# RESULTS

# Visualization

[Click here to view the Tableau Dashbord](https://public.tableau.com/app/profile/kcav18/viz/UNCCBootcampFinalProject/CMPDCrimeOverview?publish=yes)

# Linear Regression Model

Using the counts of crime per month, we will predict how many crimes will occur in the next time period. A linear regression model is used to predict a continous variable, which in our case is crime. Utilizing the data from the CMPD database we can break the data into months and then use previous data to predict violent crimes frequency and how much it will increase or decrease given a certain month or day. What we are hoping is to see strong correlations in the data that will help determine how dangerous Charlotte is; by determining the frequency of crimes with our model.

 **Purpose of Model
  
   We believe that our predictive test will be useful to Real Estate Developers, Residents, Tourists, and Businesses. It can show which month of the year will see the most crime. This data could be used to prevent civilians and businesses from making costly errors that could lead to huge financial and personal losses. In addition, this analysis could be used to make the city safer by identifying which areas see the most crime. This can assist City Leaders in making the necessary changes to decrease criminal activity in the area.
   
**Week of 2/16/23: We have ran into issues getting the model to work. Ryan is working with Antonio tonight to get the model working more effectively. We need to update the variables to predict type of crime by month** 

# SUMMARY
Based on our analysis, we feel that Charlotte would be a safe enough option for Secret Jones. According to our Heat Map, the northern part of the county would be the safest area.
According to our Machine Learning Model, __________.

# Team Roles

Ryan Marshall is going to develop the machine learning and will develop a linear regression model.

Kimberly Cavazos is our team lead visual design and will utlize Tableau to give visual context to the data and the results of our test. She will also put the final presentation together.

Fiston Rugwiro is our team lead python and ETL responsible for getting us the data cleaned in order to test.

Brenton Ervin is going to import everything into Postgress and revviewing all project elements.


    

