# HollywoodMoviesData-DataViz-UsingTableau
The original dataset that has been used for constructing the visualization can be found using the following link: ‘https://d17h27t6h515a5.cloudfront.net/topher/2017/January/587e7057_movies/movies.csv’. Can directly view the original 'movies_original.csv' file uploaded on the file section too! I have performed data cleaning and pre-processing steps (using Jupyter Notebook) on the dataset to convert the dataset into a executable form from the visualization point of view.

The tableau visualization can be directly viewed using the following link: (Tableau Link)
https://public.tableau.com/profile/shrivastavarmeghna#!/vizhome/MovieGenre_DataViz_Story_Workbook/MovieGenre_DataViz_Workbook

Cleaning Movies Data for Tableau Visualization:
I tried performing cleaning and processing steps on the original dataset (movies_original.csv) using Jupyter notebook. This allowed me to open the file using pandas read_csv module.

Data clean up:
If we look at the dataset the information needed to answer the questions isn't readily available. We need to do some preprocessing on relevant columns to dig out the information needed to answer the questions. I started by fixing the columns that pertain to the question I am trying to address.

Questions that can be answered:

Question 1: How have movies based on novels performed relative to movies not based on novels? 
Question 2: How have movie genres changed over time? 
Question 3: How do the attributes differ between Universal Pictures and Paramount Pictures? (In progress. The dataset has been tweaked taking this question into the consideration)

The Final dataset consists of additional metrics that are calculated from the visualization point of view.

The dataframe generated using Jupyter Notebook is converted to csv file for Tableau visualization (movies_cleaned_genres_final.csv).


