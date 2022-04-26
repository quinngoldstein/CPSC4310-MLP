# CPSC4310-MLP
Repo for machine learning project for Seattle University's CPSC4310 course.

MLP2 Dataset information:
kc_house_data.csv:
This dataset contains data about sales of homes in King County between May 2014 and May 2015. Although this data is several years old, we still felt that it is useful to look at trends in house sales. Prior to data preprocessing, the size of this dataset is 21 columns and 21,613 rows of data points. Below are brief descriptions of each column in the dataset.

id: A unique identifier integer value for each data point.
date: The date of the sale, formatted as a single string in YYYYMMDDT000000 format. No time is given and just the date is needed.
price: The price the house was sold at, in US dollars.
bedrooms: The number of bedrooms in the house.
bathrooms: The number of bathrooms in the house.
sqft_living: The square footage of the living space in the house.
sqft_lot: The square footage of the entire lot the house is on.
floors: The number of floors the house has.
waterfront: Binary classifier if the house is waterfront or not. 0 is not waterfront, 1 is waterfront.
view: A numeric index for the quality of the view of the property on a scale of 0 to 4, with 4 being the best.
condition: A numeric index for the condition of the house on a scale of 1 to 5, with 5 being the best.
grade: A numeric index of the construction design and grade on a scale of 1 to 13, with 1-3 being poor and 11-13 being high quality.
sqft_above: The square footage of the living space above ground level.
sqft_basement: The square footage of the interior housing space below ground level.
yr_built: The year the house was first built.
yr_renovated: The year the house was last renovated. A value may be 0 if it has never been renovated.
zipcode: The zipcode of the house.
lat: The latitude of the house.
long: The longitude of the house.
sqft_living15: The square footage of the living space of the nearest 15 neighbors.
sqft_lot15: The square footage of the entire lot of the nearest 15 neighbors.