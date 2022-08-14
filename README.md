# Capstone-

Document Process

Step 1. Scope the project  and collect the data
    Exploratory data analysis and date cleansing 
Step 2. Explore and investigate the data
    Data analysis
Step 3. Define the Data Model
Step 4. Run ETL and Model the data 
Step 5. Complete project write up and submit 




Describe and Gather Data
Describe the data sets you're using. Where did it come from? What type of information is included?

Following datasets are used for this project:

I94 Immigration Data 2016: This data comes from the US National Tourism and Trade Office.


U.S. City Demographic Data: This data comes from OpenSoft.


Address assuming scenarios:
1. If the data was increased by 100x:
Data sets' size increase to 200Gb - the bigger size database will need more time more resources (Ram, CPU) to process. Amazon EMR cluster can be used with Apache Spark installed to process the increase in data 


2. The data populates a dashboard that must be updated on a daily basis by 7am every day.
The airflow tasks can be scheduled to run every morning before 7am to ensure the data is up to date and ready to be used


3. If the database needed to be accessed by 100+ people:
The more users will bring the more cpu resource to keep a good experience.
 
