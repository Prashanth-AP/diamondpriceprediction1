Diamond Price Prediction

There are 10 independent variables (including id): The dataset The goal is to predict price of given diamond (Regression Analysis).

id : unique identifier of each diamond
carat : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
cut : Quality of Diamond Cut
color : Color of Diamond
clarity : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
depth : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
table : A diamond's table is the facet which can be seen when the stone is viewed face up.
x : Diamond X dimension
y : Diamond Y dimension
x : Diamond Z dimension

Target variable:

price: Price of the given Diamond.

Dataset Source Link : https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv

Simple linear Regression
Simple Linear Regression is a type of Regression algorithms that models the relationship between a dependent variable and a single independent variable. The relationship shown by a Simple Linear Regression model is linear or a sloped straight line, hence it is called Simple Linear Regression.

The key point in Simple Linear Regression is that the dependent variable must be a continuous/real value. However, the independent variable can be measured on continuous or categorical values.

Task Performed:
Data Cleaning
Exploratory Data Analysis
Data Preprocessing and feature engineering
Model training
Pickelizing model
Creating flask app for model

Tech Stack
Client: Flask

Server: Python, Machine Learning, Statistics, Oops

Support
For support, email apprashanth11@gmail.com

Run Locally
Clone the project

  gh repo clone Anirudhrarao/DiamondPricePrediction
Install dependencies

  pip install -r requirements.txt
Training model

  python src\pipelines\traning_pipeline.py
Start the server

  python application.py