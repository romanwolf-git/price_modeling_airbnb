# Airbnb Melbourne

In this project I worked with Airbnb data from insideairbnb.com for Melbourne.
My overall aim is to predict the price of an Airbnb. In order to reduce the number
of features, improve model performance and avoid overfitting I conduct a 
correlation analysis using Pearson's correlation, phi-k and variance thresholding.

## Table of Contents

1. [Installation](#installation)
2. [Features](#features)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

1. Download and install Jupyter Notebook: conda install jupyter or pip install jupyter
2. Clone the repository: git clone https://github.com/romanwolf-git/Airbnb_Melbourne.git
2. Install packages: 'conda install --file requirements.txt' or 'pip install requirements.txt'
3. Run the notebook and execute the cells.

## Features <a name="features"></a>

* Pearson's correlation
* Phi-k correlation matrix
* Significance matrix
* Variance thresholding
* Price prediction with LGBMRegressor
* Plotting of learning curves with cross validation
* Model tuning with Optuna

## Project Motivation<a name="motivation"></a>

For this project, I used Airbnbn data from insideairbnb.com to answer following questions:

1. Can a simple regression model be created to predict the price of an Airbnb? What is the model's predictive error?
2. Can over- or underfitting be ruled out based on learning curves?
3. Can feature selection using Pearson's correlation, ϕk-correlation, and variance thresholding help improve the model's predictive error? How does model tuning impact the model's performance?

## File Descriptions <a name="files"></a>

There is one jupyter notebook called kill_your_darlings.ipynb,
the base data called listings.csv and the requirements.txt

## Results<a name="results"></a>

I wrote an article on medium.com on my findings which you can find [here](https://medium.com/@romanwolf_22352/kill-your-darling-features-bc5dc62c47ef).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to insideairbnb.com for the data. 
