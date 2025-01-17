# Crowdfunding_ETL

- Repo Files -
ETL_Mini_Project_edonoho.ipynb is a jupyter notebook which reads in Resources/crowdfunding.xlsx and cleans the data into a pandas dataframe. This xlsx file contains data for a number of different crowdfunding projects. The data is cleaned to organize the categories and subcategories for each project. Various columns were renamed and had thier data types changed to help clarify each columns' purposes. The files campaign.csv, category.csv, and subcategory.csv and all exported to the Resources folder based on this xlsx file. 

    Next, Resources/contacts.xlsx is read in and cleaned and exported as contacts.csv into the Resources folder. This xlsx file contains contact information for many different individuals associated with various crowdfunding projects from the crowdfunding.xlsx. Again, various columns were renamed and had thier data types changed to help clarify each columns' purposes.
    
table_relation_chart.png is a png file of a chart showing how each of the data from the four exported csv files from ETL_Mini_Project_edonoho.ipynb are related. This graph was made through the QuickDBD website: https://app.quickdatabasediagrams.com/#/

Resources/crowdfunding_db_schema.sql is a schema file to create a database in PostgreSQL. After running the schema file in a new database, the tables will be imported from the same named csv files in the Resources folder. The csv files must be imported in the following order to avoid errors: contacts.csv -> campaign.csv -> category.csv -> subcategory.csv.

- Collaboration -
I worked with various students in class with this project as this was a fairly collaborative project. I did the vast majority of the work myself and this work reflects my own understanding of the material. 
