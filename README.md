# MovieLens-Viz

This repo is for **Caltech CS155: Machine Learning and Data Mining** (2020 Winter) miniproject2. 

**Goal**: create visualizations of the MovieLens dataset using matrix factorization

The MovieLens data set consists of 100,000 ratings from 943 users on 1682 movies, where each user has rated at least 20 movies.

This repo contains:

- `movies.txt`: 
  - Each of the 1682 lines in this file contains a tab-delimited list of the following fields for a movie: 
  
  ```Movie Id, Movie Title, Unknown, Action, Adventure, Animation, Childrens, Comedy, Crime, Documentary, Drama, Fantasy, Film-Noir, Horror, Musical, Mystery, Romance, Sci-Fi, Thriller, War, Western```
  
  The last 19 fields are various movie genres. Here, a 1 indicates the movie is of the given genre, while a 0 indicates that it is not. Note that movies can be in several genres at once. The movie ids correspond to the movie ids specified in the data.txt file and range from 1 to 1682.
  - There may be movies with duplicate titles but different ids in this dataset.
  - Some of the movies do not have reviews at all.

- `data.txt`:
  - Each of the 100,000 lines in this file consists of a tab-delimited list of the following fields for a given rating instance:
  
  ```
  User Id, Movie Id, Rating
  ```
  Here, all ratings are integer values ranging from 1 to 5. User ids range from 1 to 943 and movie ids range from 1 to 1682, as in `movies.txt`.
 
- A Jupyter notebook for data processing, basic visualizations, matrix factorization and its visualizations
- Visualization plots
- A project report
