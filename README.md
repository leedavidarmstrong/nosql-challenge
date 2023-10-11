# nosql-challenge
# The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. 
# Food magazine, Eat Safe, Love, want to help their journalists and food critics decide where to focus future articles.
# We will evaluate some of the ratings data. 
# Import the data provided in the establishments.json file.
# Using PyMongo and Pretty Print (pprint).
# Confirm that uk_food database is listed. List the collection(s) in the database to ensure that establishments is there.
# An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis.
# Find the BusinessTypeID for "Restaurant/Cafe/Canteen", Update the new restaurant with the BusinessTypeID. 
# The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database. 
# Eat Safe, Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.
# RatingValue refers to the overall rating decided by the Food Authority and ranges from 1-5. The higher the value, the better the rating.
# The scores for Hygiene, Structural, and ConfidenceInManagement work in reverse. This means, the higher the value, the worse the establishment is in these areas.
# Explore the database, and find the answers, so you can provide them to the magazine editors.
# Which establishments have a hygiene score equal to 20?, Which establishments in London have a RatingValue greater than or equal to 4?, What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?, How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


