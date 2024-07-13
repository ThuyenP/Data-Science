# Canada Real Estate Price Prediction

### Goal
Inspired by Zillow and the current real estate market price, I built a real estate price prediction model for Canada housing market with input criteria including the numbers of beds and baths and the price per square feet of user's desire value.

### Result
The model successfully predict the housing price with the accuracy of approximately 91% by using Decision Tree Regressor in Scikit Learn library. 

### Resources
#### Dataset
The dataset being used is taken from the public data source [Housing Price & Real Estate - 2023](https://www.kaggle.com/datasets/reenapinto/housing-price-and-real-estate-2023) on Kaggle. This dataset has 8 columns, which are Address, Price, Housing Description, Place (the town the house located in), Beds, Bath, Sq.Ft (Square Feet), and Website (the source of the retreived data). After data inspection and clearning, I made changes to dataset. In particular, I created a new column to calculate the price per square feet (sqft) of each house, and I also dropped 4 columns: Address, Housing Description, Place, and Website. 

##### Data Inspection
