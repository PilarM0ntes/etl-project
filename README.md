## ETL-project
Using Kaggle as a data source we are migrating 10 different csv files to a production data base. Extraction, Transformation and Load of the data was performed. 

The source of data used, and the type of transformation applied to the data to load is outlined below:

## Extract
* Data source: [Kaggle](https://www.kaggle.com/datasnaek/youtube-new)
* Use a for loop to extract data from each csv in a folder file.
* Use Jupyter notebook to create two dataframes for the ETL project.

## Transform
* Combine all dataframes from each csv file into one.
* A column with the country code was added to differentiate between countries. 
* For data cleaning the data was divided into two dataframes: Videos_df and All_Countries; to avoid redundant information. 
* Resetting the index for the videos_df and all_countries dataframes.

## Load
* Declare the database: Youtube_db
* Declare the collections: popular_videos and country_records
* Insert the dataframes in the MongoDB collections
* Convert the dataframes to dictionaries

## Team members
* Pilar Montes
* Erick Macias
* Jose Vazquez
* Marisela Castillo
