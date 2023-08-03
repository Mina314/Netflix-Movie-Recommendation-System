# Netflix-Movie-Recommendation-System-R

In this project, I developed a Movie Recommendation System using content-based and collaborative filtering recommendation techniques, as well as a hybrid approach to provide personalized movie recommendations to users.

### Technologies and Libraries Used:

* R
* recommenderlab
* ggplot2
* data.table
* reshape2
  
### Project Overview:

1. Importing Libraries and Retrieving Data:

Imported required R libraries, including recommenderlab, ggplot2, data.table, and reshape2.
Retrieved movie data from the "movies.csv" file and rating data from the "ratings.csv" file.
Conducted data exploration and summary statistics for the movie and rating datasets.
User-Based Collaborative Filtering (UBCF) Model:

2, Prepared the rating matrix by converting the rating data into a sparse matrix using recommenderlab.

Explored different parameters and implemented user-based collaborative filtering (UBCF) using the Cosine similarity measure with 10 nearest neighbors.
Generated movie predictions for the first user based on user-based collaborative filtering.

3. Data Pre-processing and One-Hot Encoding:

Performed data pre-processing, including one-hot encoding of the movie genres to facilitate further analysis.

4. Exploring Data and Visualizations:
   
Explored the similarity between users and movies using collaborative filtering techniques.
Visualized user similarities and movie similarities through heatmaps and plots.
Analyzed movie views and created a visualization of the most viewed movies.

5. Performing Data Preparation:
   
Selected useful data by filtering movies and users with a minimum number of ratings (50).
Normalized and binarized the data for better model performance.

6. Collaborative Filtering System Building:
   
Built an item-based collaborative filtering (IBCF) recommendation system using the recommenderlab package.
Split the dataset into training and testing sets (80% training, 20% testing) for evaluation.
Visualized the similarity shared between top movie items through a heatmap.

7. Recommendation Generation and Evaluation:
   
Generated top movie recommendations for each user using the item-based collaborative filtering model.
Evaluated the performance of the recommendation system on the testing data.

