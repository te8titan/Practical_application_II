What drives the price of a car?

Overview
--------

This project analyzes the price driving parameter of used cars.
For the examination a big car dataset with around 430k entries was used.
The dataset stores the most price relevant data like cylinders, condition, fuel,
year of sold, odometer, color, model, manufacturer et. and of course the price.

Findings
--------

The analyzation was done with three models to find out which fits best for the end user.
The end user are used car seller.

The following results was found:
  # Main the most important parameter for the price driving was:
    1.) Amount of cylinders 
	2.) Age of the car
	3.) Odometer 
	4.) Condition
	5.) Fuel of the car
  # From the prediction quality the most complex model (Ridge-Model)
    comes with the best results (smallest mean squared error).
	From the practical use for the car seller it is to complex to compute.
	There are 54 attributes for computing the price of a car.
  # From the easy to use side the "Lasso-Model" comes with only 5 attributes to 
    compute.
	The exact parameter will be shown in the attached jupyter notebook file (practial_app_II.ipynb).
  # The region or state where the car could be sold are not relevant to the price.
  

Recommendation
--------------

The prediction could be more precised if the attributes (cylinders, age, odometer, condition, fuel) are given
for all cars in the dataset. 

The best suitable model is the Lasso-Model and could be integrated in a Excel calculation sheet.
