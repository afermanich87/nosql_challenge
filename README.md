# nosql_challenge

## Part 1: Database and Jupyter Notebook Set Up
Use `NoSQL_setup_starter.ipynb` for this section of the challenge.

Import the data provided in the `establishments.json` file from your Terminal. Name the database `uk_food` and the collection `establishments`. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

* Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

* Create an instance of the Mongo Client.

* List the databases you have in MongoDB. Confirm that uk_food is listed.

* List the collection(s) in the database to ensure that establishments is there.

* Find and display one document in the establishments collection using find_one and display with pprint.

* Assign the establishments collection to a variable to prepare the collection for use.


## Part 2: Update the Database
Use `NoSQL_setup_starter.ipynb` for this section of the challenge.

Add the new restaurant into the database and and convert the string values to decimals for longitude and latitude.


## Part 3: Exploratory Analysis

Use `NoSQL_analysis_starter.ipynb` for this section of the challenge.

follow the prompts in jupyter notebook to finish the analysis.

Note: 
* RatingValue refers to the overall rating decided by the Food Authority and ranges from 1-5. The higher the value, the better the rating. This field also includes non-numeric values such as 'Pass', where 'Pass' means that the establishment passed their inspection but isn't given a number rating.

* The scores for Hygiene, Structural, and ConfidenceInManagement work in reverse. This means, the higher the value, the worse the establishment is in these areas.




## References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
