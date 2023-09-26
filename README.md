# Crowdfunding_ETL
In this project we had to update the Crowdfunding file and from that file create 3 separate files.


# Category File 
  Created from a single column in Crowdfunding (Category/Subcategory-column header).
  Within the Category file, the Category/Subcategory column is split into Category and Subcategory respectively.
  Once the columns populated, a new column was created labeled category id and the id was associated to a category name (i.e food). 
  After that a new csv was created labled **category.csv**.

  
# SubCategory File 
  Created from a single column in Crowdfunding (Category/Subcategory-column header).
  Within the SubCategory file, the Category/Subcategory column is split into Category and Subcategory respectively.
  Once the columns populated, a new column was created labeled subcategory id and the id was associated to a subcategory name (i.e food trucks). 
  After that a new csv was created labeled subcategory.csv.

# Contacts File
Imported the "contacts.xlsx" file into a DataFrame. Iterated through the DataFrame, converting each row to a dictionary. Extracted the dictionary values from the keys using Python list comprehension. Created a new DataFrame containing the extracted data. Split each "name" column value into "first name" and "last name" columns. Cleaned and exported the DataFrame as "contacts.csv."

# Database Schema Design
  Once the 4 fields were created, they were added back into the original DataFrame (Crowdfunding), that updated   Dataframe was then exported and renamed **campaign.csv**
  
  To design the database schema, we followed these steps:

  Inspected the four CSV files and gathered information.
  Sketched an Entity-Relationship Diagram (ERD) based on the tables' relationships.
  Used the ERD as a reference to create a table schema for each CSV file, ensuring data integrity and consistency.
