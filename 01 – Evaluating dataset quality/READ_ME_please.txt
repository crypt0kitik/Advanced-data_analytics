Evaluating dataset quality

Goal: Evaluate the quality of datasets.

1. In this project, I have two datasets. I started with the classification dataset, which is about IMDb movie ratings. For this dataset, I tested the following tools:
- Autoviz
- Dataprep
- LIME
- Phik-matrix
- Sweetviz
- Ydata

After that, I performed the same operations on the regression dataset, with additional tests:
- Seaborn polynomial test
- MAD test

Regression Dataset:
The target variable is a continuous value, which is the movie rating.
The link for the dataset: https://www.kaggle.com/datasets/kianindeed/imdb-movie-dataset-dec-2023  

Classification Dataset:
The target variable is a classification target with two options: whether a loan is taken (yes/no).
The link for the dataset: https://www.kaggle.com/datasets/rouseguy/bankbalanced

GitHub Link: For the manual EDA of these datasets, which I performed last year:
https://github.com/crypt0kitik/Introduction-to-Machine-Learning-Methods/tree/main

2. Time series dataset evaluation

I did not have experience with time series datasets, 
which is why this part of the project was quite challenging. 
I tried different methods of analysis such as:
- ProfileReport
- TsFresh (for feature extraction)
- Kats
- AutoTS (for automated time series analysis)

They all had issues either with installing libraries or with the format of the columns. However, I successfully managed to work with:
- Prophet