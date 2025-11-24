# MovieLens Exploratory Data Analysis (EDA) and Feature Engineering

##  Project Overview

This repository contains an **Exploratory Data Analysis (EDA)** and **Feature Engineering** project on the **MovieLens** dataset.

The primary goal is to clean, transform, and analyze the dataset to derive meaningful insights that can inform the development of a movie recommendation system. The analysis covers user rating patterns, movie popularity trends, genre distribution, and time-based activity.

##  Dataset

The project utilizes the **MovieLens** dataset (specifically a smaller version, like `ml-latest-small`), which typically includes:

* **ratings.csv**: User ratings for movies.
* **movies.csv**: Movie titles and their genres.
* **tags.csv**: User-generated tags for movies.

The final output of the analysis is a comprehensive, merged, and cleaned dataset.

##  Features & Analysis Highlights

The core of the project is documented in the **`MovieLens_EDA.ipynb`** Jupyter Notebook, which includes:

1.  **Data Loading and Merging**: Combining `ratings`, `movies`, and `tags` into a unified DataFrame.
2.  **Feature Engineering**:
    * Extracting **release year** from movie titles.
    * Calculating **genre-specific features** (e.g., one-hot encoding for genres).
    * Extracting **day of the week** and **hour of the day** from timestamps to analyze user activity.
    * Calculating **movie popularity metrics** (e.g., number of ratings, average rating).
3.  **Exploratory Data Analysis (EDA)**: Visualizations and statistical summaries of rating distribution, most popular genres, user activity, and the correlation between popularity and average rating.

##  Key Findings & Insights

The analysis yielded several important insights for a recommendation engine:

1.  **Popular Genres**: **Drama**, **Comedy**, and **Action** are consistently the most frequently rated genres.
2.  **Top-rated movies**: The highest-rated movies are often independent or less-known classics, indicating high-quality niche preferences.
3.  **Rating Distribution**: The majority of ratings are skewed towards **4.0** and higher, suggesting users are more likely to rate movies they enjoy.
4.  **Tags**: User tags show engagement trends (e.g., “classic”, “funny”, “sci-fi” appear often).
5.  **Activity Pattern**: Rating activity significantly peaks around **weekends**.
6.  **Correlation**: Movies with a very high number of ratings often have slightly lower average ratings — a common popularity trade-off.

These insights are crucial for designing a robust recommendation system that balances popularity with niche preferences.

## 📂 Repository Structure
Element,Type,Description
### data/,Directory,"Storage location for all datasets, both original and processed/cleaned. It keeps the project root clean."

#### ratings.csv,File,Original dataset file (assumed). Contains user ratings of movies. Essential for building recommender systems or analyzing rating patterns.

#### movies.csv,File,"Original dataset file (assumed). Contains movie metadata, including titles and genres. Used for joining with ratings and tags."

#### tags.csv,File,Original dataset file (assumed). Contains user-submitted tags for movies. Useful for feature engineering and content-based analysis.

#### cleaned_movielens.csv,File,"Output/Engineered Dataset. The final, cleaned, merged, and feature-engineered dataset ready for modeling or deep analysis. This is the main input for the analysis notebook."

#### MovieLens_EDA.ipynb,File,"Jupyter Notebook. The main workspace for Exploratory Data Analysis (EDA), cleaning scripts, feature engineering, and initial analytical findings on the MovieLens dataset."

## 👤 Author

**Japhet Ujile**
📧 [assistant.rawlings@gmail.com](mailto:assistant.rawlings@gmail.com)
🌐 [GitHub](https://github.com/assistantrawlings-lgtm) | [LinkedIn](https://www.linkedin.com/in/japhet-ujile-838442148?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app])
