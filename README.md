# Movie-Recommendation-System
A system which gives personalised recommendations for users based on their previous rating for movies and similar user's rating history.


Pandas is used to preprocess the dataset from movielens. Cosine similarity is also used to get the idea about how related two users are based on their previous rating to various movies that the current user has watched already.
<br/>
<br/>
This concept works on the basis that similar users with similar taste in movies would tend to like the same movies in the future.
Similar users are calculated using the ratings given by the users perviously and cosine similarity is used here.
<br/><br/>
The final csv file with the relationship weightage is exported and used in Neo4j to find the results for specific users.
Neo4j is graph database which gives importance to relationship weights something which SQL and MonogoDB doesn't provide.
The queries are uploaded in github for the reference.
