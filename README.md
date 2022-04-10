# Group Project for DSCI 100 at UBC
Students will work together in groups to complete a Data Science project from the beginning (downloading data from the web) to the end (communicating their methods and conclusions in an electronic report). The electronic report will be a Jupyter notebook in which the code cells will download a dataset (chosen from the list of options below) from the web, reproducibly and sensibly wrangle and clean, summarize and visualize the data, as well as appropriately answer a predictive question. Markdown cells will be used throughout the document to narrate the analysis to communicates the question asked, methods used and the conclusion reached.

For this project, we are answering the predictive question about a weather dataset from https://www.kaggle.com/ananthr1/weather-prediction using KNN classification.

Download project_report.html and open locally, or download project_report.ipynb and with jupyter. Optionally, clone this repo!

## Project Overview - Predicting Type of Weather
We use the K-nearest neighbours classification algorithm to classify the type of weather based on 3 predictors: daily precipitation, average temperature and minimum temperature. Weather is classified as either: rain, sun, snow, drizzle,or fog. Our model predicts on a subset of the data with 75.8% accuracy.

We use a naive version of the forward selection method to select our predictor variables. We tune our model using cross validation. Finally, we evaluate our model by analyzing its accuracy metrics. Throughout the notebook, we provide visualizations of our data and model, as well as tables and explanations for each step.

In defining our project goals, we chose to work with weather data because of its broad range of applications. We can use data science techniques to help people better understand and predict weather, seasonal, and climate trends. Such knowledge is useful in daily life, business, and agriculture, etc. Our project barely scrapes the surface of what is possible.

## Technology Used
R - language for statistical computing and graphics
Jupyter Lab - server-client app for running notebooks
Git/GitHub - version control and remote repo hosting
