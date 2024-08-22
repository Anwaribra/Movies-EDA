# Movie Dataset Analysis

This repository contains analysis and data cleaning operations on a movie dataset. The dataset includes various features related to movies, such as the director, cast, budget, IMDb score, and social media metrics.

## Dataset Overview

The dataset contains 4,916 entries with 28 columns, including:

- **color**: Whether the movie is in color or black-and-white.
- **director_name**: The name of the director.
- **duration**: Duration of the movie in minutes.
- **gross**: Gross earnings of the movie.
- **genres**: Genres associated with the movie.
- **budget**: Budget of the movie.
- **imdb_score**: IMDb rating score.
- **movie_facebook_likes**: Facebook likes for the movie.

... (Include descriptions for other relevant columns)

## Data Cleaning Process

The dataset was cleaned and prepared for analysis using the following steps:

1. **Handling Missing Values**:
   - Numeric columns were filled with the median value.
   - Categorical columns were filled with the mode value.
   - Columns with more than 50% missing values were dropped.

2. **Data Type Conversion**:
   - Ensured correct data types for columns like `title_year`, which was converted to `int64`.

3. **Removing Duplicates**:
   - Duplicate rows were identified and removed to ensure data integrity.

4. **Standardizing Data**:
   - Ensured consistency in categorical data such as `color` and `content_rating`.




