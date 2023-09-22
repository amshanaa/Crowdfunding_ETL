# Crowdfunding_ETL
In this project we had to update the Crowdfunding file and from that file create 3 separate files.
Category File-this is a file created from a single column in Crowdfunding (Category/Subcategory-column header).
  Within the Category file, the Category/Subcategory column is split into Category and Subcategory respectively.
  Once the columns populated, a new column was created labeled category id and the id was associated to a category name (i.e food). 
  After, that a new csv was created labled category.csv
SubCategory File-this is a file created from a single column in Crowdfunding (Category/Subcategory-column header).
  Within the SubCategory file, the Category/Subcategory column is split into Category and Subcategory respectively.
  Once the columns populated, a new column was created labeled subcategory id and the id was associated to a subcategory name (i.e food trucks). 
  After, that a new csv was created labled subcategory.csv
Once the 4 fields were created, they were added back into the original DataFrame (Crowdfunding), that updated Dataframe was then exported and renamed campaign.csv
