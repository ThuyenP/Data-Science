# Canada Real Estate Price Prediction

### Goal
Inspired by Zillow and the current real estate market price, I built a real estate price prediction model for Canada housing market with input criteria including the numbers of beds and baths and the price per square feet of user's desire value.

### Result
The model successfully predict the housing price with the accuracy of approximately 91% by using Decision Tree Regressor in Scikit Learn library. 

### Resources
#### Dataset
The dataset being used is taken from the public data source [Housing Price & Real Estate - 2023](https://www.kaggle.com/datasets/reenapinto/housing-price-and-real-estate-2023) on Kaggle. This dataset has 8 columns, which are Address, Price, Housing Description, Place (the town the house located in), Beds, Bath, Sq.Ft (Square Feet), and Website (the source of the retreived data). After data inspection and clearning, I made changes to dataset. In particular, I created a new column to calculate the price per square feet (sqft) of each house, and I also dropped 4 columns: Address, Housing Description, Place, and Website. 
* Data Inspection
  * Outlier Detection:
   During the data inspection process, I found out there are 2 main outlier datapoints in the set based on the number of bedrooms in the house. In particlar, there are only 8 houses for 8 bedrooms and 1 house for 10 bedrooms while there are more than 100 records for other type of bedrooms ranging from 1 to 7. The statistical calculation showed that those datapoint lies outside the 3 unit of standard deviation for the data, hence showing that the datapoint of 8- and 10-bedroom houses are the outliers.
  * Outlier Solution:
   Since the dataset is large (with approximately 3500 datapoints), I decided to drop these outlier points and proceed with the model building.

#### Techonologies
