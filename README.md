
# Diamond Price Prediction

There are 10 independent variables (including id): The goal is to predict price of given diamond (Regression Analysis).

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


## Task Performed:
1.Data Cleaning
2.Exploratory Data Analysis
3.Data Preprocessing and feature engineering
4.Model training
5.Pickelizing model
6.Creating flask app for model


## Tech Stack

**Web development:** HTML,Flask.

**Programming Language:** Python.

**Python packages:** Scikit-Learn,Pandas,Numpy.

## Screenshot

![Screenshot 2024-11-09 131112](https://github.com/user-attachments/assets/9056fc2e-dfb5-4ec3-8f20-f0a92cc76fa7)
## Results
- The Decision Tree Model is the best Model among Ridge,Lasso,      Elastic and LinearRegression models for this Project.

- The Model is able to Perform well for the test data with the r2 score : 95.50%