This repository contains self-contained Recommendation System examples.

### Table of Contents
  - <a href='#movie-recommender-using-imdb-calculation'>Movie Recommender-IMDB Calculation</a> 
  - <a href='#movie-recommender-using-parameter-filtering'>Movie Recommender-Parameter Filtering</a> 
  - <a href='#movie-recommender-using-collaborative-filtering'>Movie Recommender-Collaborative Filtering</a> 
  - <a href='#movie-recommender-using-contentbased-filtering'>Movie Recommender-Contentbased Filtering</a> 
  - <a href='#grocery-recommender-using-apriori-algorithm'>Grocery Recommender-Apriori Algorithm</a> 
  
<hr>
 
- ###### [Movie Recommender using IMDB Calculation](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-IMDB) 
   ###### This example illustrates how to recommend movies on the basis of IMDB Formula. [[Source Code]](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-IMDB)  
   * Load the Dataset [movies_metadata.csv]
   * Apply IMDB Formula
   ![image](https://user-images.githubusercontent.com/689226/50198368-53956c00-0371-11e9-9fc4-e5c082c351af.png)
   * Sort movies based on score calculated 
   * Get the top n movies
   ![image](https://user-images.githubusercontent.com/689226/50198225-a6baef00-0370-11e9-8a19-5e33f59090f8.png)

    
 <hr>
 
- ###### [Movie Recommender using Parameter Filtering](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-ParameterFiltering)
   ###### This example recommends latest movies on the basis of various filters applied on the Dataset. [[Source Code]](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-ParameterFiltering)
  * Load the Dataset [movies_metadata.csv]
  * Filter by adult/Non-Adult Movie
  * Filter by year
  * Filter by Vote Count
  * Filter by Run time
  * Filter by Vote Average
  * Filter by Genres
 
 
  <hr>
  
- ###### [Movie Recommender using Collaborative Filtering](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-CollaborativeFiltering)
   ###### This example demonstrates the concept of User-User Similarity and Item-Item Similarity. [[Source Code]](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-CollaborativeFiltering)
  * Load the Dataset [u.data]
  * Create User-Movie Rating Relationship Table
  * Cater Missing Values
  * Prepare User-User Similarity Matrix Dataframe [Cosine Metric]
  * Handle diagnols
  * Create Movie-User Rating Relationship Table
  * Cater Missing Values
  * Prepare Item-Item Similarity Matrix Dataframe [Correlation Metric] 
  ![image](https://user-images.githubusercontent.com/689226/51094920-d970cf80-17d6-11e9-9c60-647d190a0982.png)
  * Load the Dataset [u.item]
  * Prepare user defiend functions to compute Recommendations.
 

    <hr>
    
 - ###### [Movie Recommender using Contentbased Filtering](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-ContentBased)
   ###### This example demonstrates the concept of Content based Similarity (TF-IDF). [[Source Code]](  https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/MovieRecommender-ContentBased)
  * Load the Dataset [movies_metadata.csv | metadata_clean]
  * Compute TF-IDF on movie description.
  * Prepare user defiend functions to compute Content based Recommendations.
 
    <hr>
  
    
- ###### [Grocery Recommender using Apriori Algorithm](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/GroceryRecommender-Apriori)
   ###### This example demonstrates the theory and implementation of Apriori Algorithm. [[Source Code]](https://github.com/rahulvaish/RecommendationSystems-Python/tree/RecommendationSystems/GroceryRecommender-Apriori)
  * Install apyori library.
  ![image](https://user-images.githubusercontent.com/689226/51730299-f5a92200-209c-11e9-8106-e5388934ae10.png)
  * Load the Dataset [grocery.csv]
  * Picked top 2000 out of total 75000 records. Apriori is very expensive in calculation and computation.
  * Convert pandas dataframe into a list of lists.(Format for Ariori Algorithm)
  * Call apriori() function with approprite parameters.
  * Examine the results.

<hr>




