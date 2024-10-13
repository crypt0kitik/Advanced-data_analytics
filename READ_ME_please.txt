Evaluating dataset quality

Goal: evaluate datasets' quality

In this project I have 2 datasets. I started to work with the regression one which is about IMBD rating movie and for this one I tested the next tools: 
- Autoviz
- Dataprer
- LIME
- Phik-matrix
- Sweetviz
- Ydata

After that the same operations I did for the linear regression dataset.

One dataset for regression purposes
Target variable is a continuous value which is rating of a movie
The link for the dataset: https://www.kaggle.com/datasets/kianindeed/imdb-movie-dataset-dec-2023  

One dataset for classification purposes
Target variable is a classification target with certain amount of options which is taking the loan - yes/no
The link for the dataset: https://www.kaggle.com/datasets/rouseguy/bankbalanced

Questions:

- Target variable distribution, is it optimal?
(normal distribution for regression is usually optimal, for classification: normal or balanced distribution)

- Independent variable distributions, are they balanced throughout the datasets?

- Overlapping data and noise, are any variables messy (lots of outliers etc.) or do they have contradicting trends, that might be non-optimal or confusing for the target -variable?
(see lecture examples regarding the red wine dataset, it has lots of these)

- Redundancy, are there any variables that probably could be removed due to redundant information?
(variables that have more or less the same effect on the dataset, thus one of them being redundant)

- Other problems in the dataset, like missing data and duplicate rows?
If so, how much missing or duplicate data there is?

- Significant outliers in the dataset?

- Ideas for performing feature engineering for this dataset: any ideas combining, altering, filtering specific columns of the dataset?

- Any other out of the ordinary in your dataset that we should keep an eye on?