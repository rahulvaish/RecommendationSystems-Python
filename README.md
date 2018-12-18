# **Branch Contents:**
#### [1] [SURPRISE](https://github.com/rahulvaish/RecommendationSystems-Python/tree/SURPRISE) : Implementation of Recommendation System using 'Surprise' Library.
- ###### Recommender using Surprise:
  * Install Surprise on Anaconda:
  ![image](https://user-images.githubusercontent.com/689226/50178672-2a51ed00-032b-11e9-83c7-cdfde20d1b50.png)  
  * Use of Pre-defined library functions to compute Recommendations.
<hr>

#### [2] [RecommendationSystems](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems) :  Various examples on different kinds of Recommendation Systems.
- ###### Movie Recommender using Collaborative Filtering:
  * Load the Dataset [u.data]
  * Create User-Movie Rating Relationship Table
  * Cater Missing Values
  * Prepare User-User Similarity Matrix Dataframe [Cosine Metric]
  * Handle diagnols
  * Create Movie-User Rating Relationship Table
  * Cater Missing Values
  * Prepare Item-Item Similarity Matrix Dataframe [Correlation Metric] 
  * Load the Dataset [u.item]
  * Prepare user defiend functions to compute Recommendations.
  
- ###### Movie Recommender using IMDB Calculation:
  * Load the Dataset [movies_metadata.csv]
  * Apply IMDB Formula
  ![image](https://user-images.githubusercontent.com/689226/50176970-d04f2880-0326-11e9-9ffb-ff8b60da9994.png)
  * Sort movies based on score calculated 
  * Get the top n movies
  
- ###### Movie Recommender using Parameter Filtering:
  * Load the Dataset [movies_metadata.csv]
  * Filter by adult/Non-Adult Movie
  * Filter by year
  * Filter by Vote Count
  * Filter by Run time
  * Filter by Vote Average
  * Filter by Genres
