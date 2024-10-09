Pick at least 500 movies from rottentomatoes.com.
Created a python notebook that scrapes as much info as possible for each movie and stores it in a csv with one line per movie.
Created a second python notebook that reads the csv file produced by the first notebook. This second notebook should then split the rows into training and testing sets (75%-25%),
trains and tunes a model for predicting a movie's AUDIENCE SCORE on the training set, and then reporting the accuracy on the testing set. 
The Audience score should be binarized: negative if it's <50% and positive if it's >=50%. 
ariables for Movie Data Scraping
The following variables will be collected from Rotten Tomatoes for each movie




Title:The name of the movie.

Genre: The genre(s) the movie belongs to (e.g., Action, Comedy, Drama).

Release Date: The date the movie was released.

Director: The name of the director.

Cast: Main actors in the movie.

Critic Score: The percentage score from critics.

Audience Score: The percentage score from the audience.

Synopsis: A brief summary of the movie plot.

Runtime: Duration of the movie in minutes.

Language: The language(s) the movie is available in.

Country: The country of origin.

Box Office Gross: Total revenue generated by the movie.

Rating: The film's rating (e.g., PG, R).

Variables for Machine Learning Model

Title: (optional, for identification)

Genre: Encoded as categorical variables.

Release Date: Extracted features like year of release.

Critic Score: Numerical value for training.
Box Office Gross: Numerical value, may indicate popularity.
Audience Score (binarized): Target variable (0 for <50%, 1 for >=50%).
These variables will be used to analyze relationships between different film characteristics and audience ratings, aiding in the model's predictive capability.
