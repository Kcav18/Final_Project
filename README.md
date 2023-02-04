# Final Project for UNCC Data Analytics Bootcamp

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
  
   We believe that our predictive test will be useful to real estate developers, tourism, and business location. This data could be used to prevent civilians and businesses from making costly errors that could lead to huge losses finacial and personal.
  
   
