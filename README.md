# What drives the price of an Airbnb?

In this project I seek for the answer to the question: "what drives the price of an Airbnb".
I answer the question by modeling the price using few statistically selected features.
My work is based on scraped data from [insideairbnb.com](http://insideairbnb.com/) for Melbourne.

## Table of Contents

1. [Installation](#installation)
2. [Features](#features)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

1. Download and install Jupyter Notebook: conda install jupyter or pip install jupyter
2. Clone the repository: git clone https://github.com/romanwolf-git/price_modeling_airbnb
2. Install packages: 'conda install --file requirements.txt' or 'pip install requirements.txt'
3. Run the notebook and execute the cells.

## Features <a name="features"></a>

* Pearson's correlation
* Phi-k correlation analysis
* Variance thresholding
* Price prediction with LGBMRegressor
* Plotting of learning curves with cross validation
* Model tuning with Optuna

## Project Motivation<a name="motivation"></a>

The goal of this project is to answer the following questions:

1. Can the price of an Airbnb be predicted? Which model predicts best with the least error?
2. What are the most important features to predict the price of an Airbnb?
3. How many features are necessary to predict the price of an Airbnb?

## File Descriptions <a name="files"></a>

There is one jupyter notebook called [what_drives_the_price_of_an_Airbnb.ipynb](https://github.com/romanwolf-git/price_modeling_airbnb/blob/main/what_drives_the_price_of_an_Airbnb.ipynb),
the base data called [listings.csv](https://github.com/romanwolf-git/price_modeling_airbnb/blob/main/listings.csv) and the requirements.txt

## Results<a name="results"></a>

I wrote an article on medium.com on my findings which you can find [here](https://medium.com/@romanwolf_22352/what-drives-the-price-of-an-airbnb-9f17019954d4).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to [insideairbnb.com](http://insideairbnb.com/) for the data.