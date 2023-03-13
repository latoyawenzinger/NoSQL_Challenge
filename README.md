# NoSQL_Challenge


The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. MongoDB was used
to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.


# **Updating the database**:
  - new halal restaurant was added to existing database, with appropriate 'BusinessTypeID'
  - deleting documents containing the 'Dover Loval Authority'
  - converting 'longitude' and 'latitude' from strings to decimal numbers
  
  # **Exploritory Analysis**:
  - Which establishments have a hygiene score equal to 20?
  - Which establishments in London have a RatingValue greater than or equal to 4?
  - What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  - How many establishments in each Local Authority area have a hygiene score of 0? 
  
