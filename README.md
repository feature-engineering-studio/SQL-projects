# SQL projects
## Possible SQL projects to hone your skills

## Level 1. Create an AWS datbase to store a personal copy of data in a specific structure

a. Spin up an AWS instance and populate it with a MySQL database  
b. Got to the [Central Park Squirrel Census](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw)  
c. Download the dataset and upload it into your SQL database  
d. Create two new tables, one that gives the squirrel sighting characteristics by primary fur color and another by secondary fur color  

## Level 2. Create an AWS database linked to an API

a. Request a developer account from Github  
b. Review the documentation on authentication (see this repo for some R code, but note that authentication is slightlty different now)  
c. Pull data from a repo you have created  
d. Upload the data into your SQL database  
e. Create separate tables that represent each day that data has been pulled from Github  

## Level 3. Create an RStudio server in the Cloud
a. Follow the directions to set up an AWS server version of RStudio [here](https://github.com/feature-engineering-studio/aws-setup)  
b. Set up your SQL database through your AWS version of RStudio  
c. Using your API script from level 2, pull some data from Github and populate the SQL database  
d. Write a SQL query that draws down pull requests for a five day time period  
e. Edit the tables to delete an requests made on a weekend  
f. Create a separate table that is populated only by pull requests that DO NOT have the word "update" in their comment field  
