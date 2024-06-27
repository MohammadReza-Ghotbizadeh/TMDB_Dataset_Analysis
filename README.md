# TMDB Movie Dataset EDA, ML, and Recommender System

## Overview

This project leverages the TMDB (The Movie Database) dataset to conduct comprehensive data analysis and build a content-based recommender system. The dataset includes detailed information about movies, such as cast, crew, genres, keywords, budget, revenue, and more.

### Project Structure

- **[TMDB_EDA.ipynb](TMDB_EDA.ipynb):** Jupyter notebook focusing on exploratory data analysis (EDA), feature engineering and visualize insights. For better visualization, visit this [link](https://nbviewer.org/github/MohammadReza-Ghotbizadeh/TMDB_Dataset_Analysis/blob/main/TMDB_EDA.ipynb).
- **[TMDB_Rec.ipynb](TMDB_Rec.ipynb):** Jupyter notebook implementing a content-based recommender system.
- **[TMDB_ML.ipynb](TMDB_ML.ipynb):** Jupyter notebook dedicated to machine learning models for predicting movie profitability. Check out this [link](https://nbviewer.org/github/MohammadReza-Ghotbizadeh/TMDB_Dataset_Analysis/blob/main/TMDB_ML.ipynb) for better visualization.
- **[requirements.txt](requirements.txt):** File listing necessary Python libraries for the project.
- **[clean_data.csv](clean_data.csv):** Preprocessed dataset used for machine learning models.
- **[Dimensions.xlsx](Dimensions.xlsx):** Multi-sheet CSV file containing the mapping tables used to categorize and provide additional context to the data in clean_data.csv, enhancing its interpretability and usability.
- **[tmdb_5000_credits.csv](tmdb_5000_credits.csv):** Original dataset containing movie credits information.
- **[tmdb_5000_movies.csv](tmdb_5000_movies.csv):** Original dataset containing movie details.
- **[TMDB_Analysis_Report.pdf](TMDB_Analysis_Report.pdf):** PDF document providing detailed analysis findings and insights.

## Files Description

- **TMDB_Analysis.ipynb**: This notebook starts with data preprocessing, explores relationships between various features and movie profitability.

- **TMDB_Rec.ipynb**: This notebook constructs a content-based recommender system that suggests similar movies based on textual data such as movie overviews, genres, and keywords. It employs techniques like CountVectorizer and TF-IDF to process textual data and computes cosine similarity for recommendations.

- **TMDB_ML.ipynb**: This notebook is dedicated to exploring different machine learning models to predict movie profitability. It includes preprocessing steps, model selection, evaluation metrics, and insights derived from the models. It explores different algorithms and evaluates their performance using appropriate metrics.

- **requirements.txt**: Contains a list of Python packages required to run the notebooks.

- **clean_data.csv**: A clean and preprocessed dataset used for training machine learning models, derived from the original TMDB dataset.

- **tmdb_5000_credits.csv** and **tmdb_5000_movies.csv**: Original datasets from TMDB containing comprehensive information about movies, including cast, crew, budget, revenue, genres, keywords, etc.

- **TMDB_Analysis_Report.pdf**: Contains an analysis report, detailing key findings and inferences from the TMDB movie dataset.

## Requirements

To run the notebooks and execute the code, ensure you have installed all dependencies listed in **requirements.txt**. You can install them using pip:

```bash
pip install -r requirements.txt
```

## Conclusion

This project showcases how data analysis, machine learning, and recommender systems can be applied to movie datasets to derive insights and build useful applications.
