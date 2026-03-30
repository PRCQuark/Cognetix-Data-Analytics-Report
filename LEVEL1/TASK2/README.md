# Movie Ratings Analysis

## Objective
Evaluate movie ratings to identify audience preferences and high-performing genres.


## Dataset
MovieLens Dataset (Kaggle)


## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


## Steps Performed
1. Loaded movies and ratings datasets
2. Cleaned data (removed duplicates, checked nulls)
3. Merged datasets using movieId
4. Calculated:
   - Average rating per movie
   - Total rating count per movie
5. Filtered top movies based on rating count (>100)
6. Performed genre analysis:
   - Split multiple genres
   - Calculated average rating per genre
   - Calculated rating count per genre
7. Visualized:
   - Rating distribution (histogram)
   - Genre performance (bar chart)
   - Genre popularity (bar chart)

## Key Insights

- Classic movies like *The Shawshank Redemption* and *The Godfather* have the highest ratings
- High rating count + high average rating indicates reliable audience preference
- Drama is the most popular genre based on engagement
- Popularity does not always mean high rating
- Ratings are mostly concentrated between 3–4
- Large dataset ensures strong analytical reliability

## Name
Rutuj Bhagwat