

### Methods Used:

1. **Import Libraries**: Importing the necessary libraries, including `numpy` and `pandas`.

2. **Get the Data**: Reading data from the "u.data" file, which contains user ratings for movies.

3. **Exploratory Data Analysis (EDA)**: Conducting exploratory data analysis to understand the dataset and calculate statistics such as average ratings and the number of ratings for movies. Includes generating histograms and joint plots to visualize data distribution and relationships.

4. **Recommending Similar Movies**:
   - **Create User-Movie Matrix**: Creating a matrix where users are rows, movie titles are columns, and each cell contains user ratings for movies.
   - **Identify Most-Rated Movie**: Identifying the movie with the most ratings in the dataset.
   - **Choose Movies**: Selecting two movies, "Star Wars (1977)" and "Liar Liar (1997)," for which similar movies will be recommended.
   - **Extract User Ratings**: Extracting user ratings for the chosen movies.
   - **Calculate Correlations**: Calculating correlations between the chosen movies and all other movies based on user ratings using the `corrwith()` method.
   - **Create Correlation DataFrames**: Creating DataFrames for the correlation results and removing NaN values.
   - **Filter by Ratings**: Filtering out movies with fewer than 100 ratings (adjustable threshold).
   - **Sort Correlated Movies**: Sorting correlated movies by their correlation scores in descending order.
   - **Display Top Recommendations**: Displaying the top recommended movies similar to the chosen movies based on user ratings.

