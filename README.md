# Kickstarter_Campaign_Modeling

This is a project that I am currently working on using a Kickstarter campaign dataset from Kaggle:
https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv

## Brief Overview:
I am using a set of 370K+ Kickstarter campaign records to find associations between
attributes and campaigns outcomes (success or failure) and build a classification
model which will predict outcomes of new records. 

** See Jupyter Notebook file for porject proogress thus far


## Detailed Outline:
* **Phase 1: Preprocessing**
    * Understanding of dataframe, attributes and missing values
    * Creation of new attributes where necessary and/or beneficial to analysis
    * Review of summary statistics
* **Phase 2: Visualization**
    * Understanding attribute relationships, distributions and occurrences using matplotlib
* **Phase 3: Association Analysis**
    * Identifying strong associations in the dataset using Apriori 
    * Further supporting previous visualization section
* **Phase 4: Classification Model**
    * Build classification model using sklearn
    * Identify right combination of attributes that leads to highest accuracy
* **Phase 5: Predicting New Campaign Instances**
    * Allows user to input new campaign info
    * Using classification model, program will tell user the likely outcome of the campaign
    * Possibly: provide association rules or tips to increase likelihood of success
* **Phase 6: Discussion**
    * Analysis applications and possible future work
