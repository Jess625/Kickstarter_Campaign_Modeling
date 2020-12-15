** Notice: Github does not render my Jupyter Notebook file in its entirety. For a more pleasant and complete rendered Notebook view, see here: https://nbviewer.jupyter.org/github/Jess625/Kickstarter_Campaign_Modeling/blob/main/Kickstarter_Campaign_Modeling.ipynb

# Kickstarter_Campaign_Modeling

Kickstarter campaign dataset from Kaggle:
https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201801.csv

## Brief Overview:
I've used 300K+ Kickstarter campaign records to find associations between
attributes and campaigns outcomes (success or failure) and build a classification
model which predicts outcomes of new records. 


## ✅ Detailed Outline of Analysis:
* **Phase 1: Preprocessing**
    * Understanding of dataframe, attributes and missing values
    * Creation of new attributes where necessary and/or beneficial to analysis
    * Review of summary statistics
* **Phase 2: Visualization**
    * Understanding attribute relationships, distributions and occurrences using matplotlib
    * Look at correlations
* **Phase 3: Association Rule Mining**
    * Identifying strong associations in the dataset using Apriori 
    * Further supporting previous visualization section
* **Phase 4: Classification Model**
    * Build classification model using sklearn
* **Phase 5: Predicting New Campaign Instances**
    * Allows user to input new campaign info
    * Using classification model, program will tell user the predicted outcome of the campaign
* **Phase 6: Discussion**
    * Analysis applications and possible future work
