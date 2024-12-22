# Audience-Rating-Prediction
It is crucial to understand how various features of a movie—such as genre, runtime, cast, director and more —affect the audience's rating. By gaining insights into these relationships, movie studios can make informed decisions about production and marketing strategies, while audiences can better anticipate how well a movie might be received. This understanding will also enable prediction of audience ratings for future movies based on their characteristics.

The goal of this project is to build a predictive model that can forecast the 'audience_rating' of a movie based on various features available in the given dataset

The dataset contains 16,638 rows and 16 columns. It is sourced from an American-based website called Rotten Tomatoes, which provides a platform for both critics and audiences to share their feedback on movies.

The ratings from critics are represented by two columns:

'tomatometer_status': This column indicates whether the movie is rated as Fresh, Rotten, or Certified Fresh by critics.

'tomatometer_rating': This column contains the numerical rating given by critics, ranging from 0 to 100.

The rating from the audience is given in the column 'audience_rating', which is also a numerical score in the range of 0 to 100, similar to the tomatometer_rating. This will be our target variable for prediction.

Other features in the dataset include columns like 'rating', 'genre', 'director', 'cast', and other movie-related information that can be used to help predict the audience_rating.
