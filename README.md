# **Movies-ETL**  


## **Overview of Project**
This is an ETL (Extract, Transform, Load) Project. The project has been done on movies data from different sources.


### **Project Summary**

The project consists of three different sections:

1. In the extract part we downloaded datasets about movies and tv shows from different data sources: a .json file from Wikipeda, a movie metadata fie and a file containing the ratings of the movies from kaggle. (due to the large size of these files we didn't upload them to this repository) 

    &nbsp;
2. to transform the data we used Python,pandas, re,... to read the files and clean them by dropping the unnecessary or almost empty columns, merging the columns containing the same information, etc. after that we merged the datasets and performed the cleaning
process again on the merged datasets.


&nbsp;

3. After finishing the transform step we sent the data to a SQL database as tables using "sqlalchemy" and "psycopg2"