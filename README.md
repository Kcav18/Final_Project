![Charlotte Image](https://github.com/Kcav18/Final_Project/blob/main/Images/Charlotte_uptown.jpeg)

# Final Project for UNCC Data Analytics Bootcamp

# OVERVIEW:

Our client, Secret Jones is looking to relocate somewhere in the United States with their family. They have been living abroad for
a long time and are ready to move back to the States. They would like a city that will not only provide a strong job and housing market, but a safe
environment for their family. Their research shows that
the job and real estate market is booming in Charlotte, NC. However, before deciding on their relocation, they are very 
interested in the violent crime data in those areas. How dangerous a place is will be a huge factor for them as their utmost concern is 
the safety of their family.

We have been tasked with analyzing the type of violent crimes occuring in Charlotte, how likely it is that a violent crime will occur, which 
area of Charlotte tends to see the most crime, and which part of Charlotte is the safest. 

Once they see the analysis of the overall crime data in the different areas of Charlotte, they would like for us to predict the frequency of violent crimes occuring per month.

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

## Visualization

[Click here to view the Tableau Dashbord](https://public.tableau.com/app/profile/kcav18/viz/UNCCBootcampFinalProject/CMPDCrimeOverview?publish=yes)

## Linear Regression Model

Using the counts of crime per month, we will predict how many crimes will occur in the next time period. A linear regression model is used to predict a continous variable, which in our case is crime. Utilizing the data from the CMPD database we can break the data into months and then use previous data to predict violent crimes frequency and how much it will increase or decrease given a certain month or day. What we are hoping is to see strong correlations in the data that will help determine how dangerous Charlotte is; by determining the frequency of crimes with our model.

 ### Purpose of Model
  
   We believe that our predictive test will be useful to Real Estate Developers, Residents, Tourists, and Businesses. It can show which month of the year will see the most crime. This data could be used to prevent civilians and businesses from making costly errors that could lead to huge financial and personal losses. In addition, this analysis could be used to make the city safer by identifying which areas see the most crime. This can assist City Leaders in making the necessary changes to decrease criminal activity in the area.
  
Unfortunately, our Machine Learning model did not work as we intended so we were unable to predict the frequency of crimes with our model.
   
Based on our analysis, we feel that Charlotte would be a safe enough option for Secret Jones. According to our Heat Map, the northern part of the county would be the safest area.

# SUMMARY

# ROADBLOCKS
- We have ran into multiple issues getting the machine model to work. Ryan has worked extensively with our instructors to get the model working more effectively. 
- We created a Postgress Database and then did not even use it because we could not get the data to work with our visualizations or machine learning model.
- Due to the Machine Learning model not working as we had hoped, we were unable to complete visualizations based on the predictions.
- We are not experts in this and have very limited training- therefore, creating a model was very challening.

# Team Roles

- Ryan Marshall: Develop the machine learning model.

- Kimberly Cavazos: Use Tableau to give visual context to the data and the results of our test. She will also put the final presentation together and ensure the Readme is up to date.

- Fiston Rugwiro: Team lead for Python and ETL.

- Brenton Ervin: Create a database and perform the necessary joins and queries.


    

