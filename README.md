# Module challenge # 12 : nosql-challenge

The task involves working with the UK Food Standards Agency's food hygiene ratings database to assist the editors of Eat Safe, Love magazine in their food reviews. The task is divided into three parts:

## Part 1: Database and Jupyter Notebook Setup
1. Database Setup:
- The data was imported from the establishments.json file into MongoDB, creating a database called uk_food and a collection named establishments.

2. Notebook Setup:
- In the Jupyter notebook, the necessary libraries (PyMongo and Pretty Print) were imported.
- MongoClient was used to verify the existence of the database and collection by listing them, and one document from the establishments collection was displayed.


## Part 2: Update the Database
1. Add a New Establishment:

- A new halal restaurant, "Penang Flavours," was added in Greenwich with relevant details, including the "NewRatingPending" flag.
Business Type Update:

2. Business Type Update:

- The BusinessTypeID for "Restaurant/Cafe/Canteen" was retrieved and used to update the new restaurant.
Data Cleaning:

3. Data Cleaning:

- Establishments in Dover Local Authority were removed.
The latitude, longitude, and RatingValue fields were converted to the correct numeric types.



## Part 3: Exploratory Analysis
1. Food Rating Analysis:

- Specific questions about ratings were answered, such as counting documents with a particular rating, displaying the first matching document, and converting results to a Pandas DataFrame. Statistics like the number of rows and the first 10 rows were displayed.

2. Key Points for Analysis:

- Ratings ranged from 1-5, with higher numbers indicating better ratings.
- Non-numeric values like 'Pass' were converted to null values.
- Hygiene, Structural, and ConfidenceInManagement scores worked in reverse (higher values indicated worse performance).
- Each analysis involved counting documents, showing the first result, converting to a DataFrame, and summarizing the findings.
