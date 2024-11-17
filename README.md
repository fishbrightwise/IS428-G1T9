# IS428-G8-T9 Visual Analytics for Business Intelligence Project Work

## How do Certain Movie Production Factors Affect a Movie’s Quality and Success?
### Purpose
The objectives of this project are:
1. Identify the movie production factors that most significantly influence a movie’s success. This will allow us to pinpoint key trends and highlight the factors most relevant to success.
2. Determine the best possible combination of each factor to predict a movie’s success. By tabulating the influence of each factor, filmmakers can estimate the likelihood of their movie’s success and make informed adjustments to improve the outcome.

### Contents
Within this repository, you will find the following:
- IPYNB Notebooks:
    1) IMDB_TMDB Data Processing <br>
    Data Processing of IMDB & TMDB Movies for Tableau.
    2) Rotten Tomatoes Critic Reviews Data Processing <br>
    Data Processing of Rotten Tomatoes Critic Reviews for Tableau.
    3) Rotten Tomatoes Movies Data Processing <br>
    Data Processing of Rotten Tomatoes Reviewed Movies for Tableau.
    4) Merging Data for Regression Prediction <br>
    Data Processing and Merging of data for Regression Analysis.
    5) Business Metrics Regression <br>
    Inital Prototype of Regression Analysis.
    6) D3 JSON Converter <br>
    Data conversion for D3.js application.
    <br><br>
- Prediction Model Application:
    1) Prediction Model Orchestrator <br>
    Main file to run Regression Analysis on.
    2) Model Training <br>
    Sub-file for Regression Model Training and Validation.
    3) Predict Success Application <br>
    Sub-file for Regression Model Prediction Application.
    4) Predict Parameters Application <br>
    Sub-file for Inverse Regression Model Prediction Application.
    <br><br>
- Tableau Notebook:
    1) Project Visualizations <br>
    Visual Analysis of Movie Data.
    <br><br>
- D3 Pages:
    1) Index Network Diagram <br>
    D3.js integrated Visual Analysis.

### Datasets
- IMDB & TMDB Movie Metadata Big Dataset (over 1M) by Shubham Chandra on Kaggle. <br>
https://www.kaggle.com/datasets/shubhamchandra235/imdb-and-tmdb-movie-metadata-big-dataset-1m/data

- Rotten Tomatoes movies and critic reviews dataset by Stefano Leone on Kaggle. <br>
https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset?select=rotten_tomatoes_critic_reviews.csv

### How to use
- For Visual Analysis:
    * Open Project Visualizations.twbx in /tableau folder.
    <br><br>
- For Regression Analysis Predictions:
    1. Download datasets and add all 3 .csv files into /data folder.
    2. Run all files in /notebooks in sequence.
    3. Run 1_prediction-model-orchestrator.ipynb in /prediction_model_application with desired input values.
- For D3 Application:
    1. Open your Terminal
    2. Navigate to the /d3 folder from your Terminal.
    3. Run the following command: python -m http.server 8000 or python3 -m http.server 8000
    4. Open your Internet Explorer and direct to http://localhost:8000/