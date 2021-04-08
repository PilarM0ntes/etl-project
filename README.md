## ETL-project
Using Kaggle as a data source we are migrating 10 different csv files to a production data base. Extraction, Transformation and Load of the data was performed. 

The source of data used, and the type of transformation applied to the data to load is outlined below:


## Extract
* Data source: [Kaggle](https://www.kaggle.com/datasnaek/youtube-new)
* Use a for loop to extract data from each csv in a folder file.
* Use Jupyter notebook to create two dataframes for the ETL project.

## Transform
* For data cleaning the data was divided into two dataframes, to avoid redundant information. 
* A column with the country code was added to differentiate between countries. 

## Load
* Declare the database
* Declare the collection
* Insert the dataframes in the MongoDB
* Insert document into collection
* Declaring the collection for countries
* Resetting index for countries dataframe
* Convert the dataframes to dictionaries

## Status
Project is: _finished_, _subject to improvement_.

## Inspiration

##Team members
* Pilar Montes
* Erick Macias
* Jose Vazquez
* Marisela Castillo
