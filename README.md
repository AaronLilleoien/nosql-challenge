# nosql-challenge

Evaluate ratings data in order to help journalists and food critics decide where to focus future articles.

Make the following changes to the establishments collection:

  A new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add their info to the db.
  
  The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within      the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.

  Some of the number values are stored as strings, when they should be stored as numbers. Convert latitude and longitude to decimal numbers.
  
  Which establishments have a hygiene score equal to 20?

  Which establishments in London have a RatingValue greater than or equal to 4?
  
  What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  
  Use aggregation method to find how many establishments in each Local Authority area have a hygiene score of 0. Sort the results from highest to lowest, and print out     the top ten local authority areas.
