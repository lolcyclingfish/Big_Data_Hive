# Big_Data_Hive

## Movie Recommendation Engine on Hive Database

The data comes from GroupLens Research Project at the University of Minnesota. They are movie ratings of users (ratings are 1-5 with 943 users and 1682 movies). The data has format: user id \t movie id \t rating \t timestamp
Given a user recommend related movies. 

Recommendation algorithem: find all pairs of movies rated by the same person with ranking higher than 3. You need to design a strategy which movie to actually recommend based on these counts.
