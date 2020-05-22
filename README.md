# Predicting-Sentiment-on-Amazon-Reviews

### Executive Summary
The Data used is from: https://www.kaggle.com/harlfoxem/housesalesprediction
<br><br>
We will be using the King County Dataset in this project, we will perform EDA, and then answer a few questions based on the data, finally we will predict the House Sale price based on a number of features using Supervised Learning Methods
<br><br>

### Pre-Processing Steps
- replaced Null values from waterfront and yr_renovated with the median, the reason being is i wanted to preserve the Median value for that column for future statistical anaylsis.
- removed Null/Missing values from view columns as it was only 63 missing points, and our dataset was fairly large enough that removing them would not have a negative effect
- changed Date column into a dtype format from integer to be able to do date time anaylsis
- removed "?" values in sqft_basement

<br><br>
### Statistical Anaylsis
- Correlation Heatmap
- Grouped Houses into prices bands depending on their sale price 
- used a heatmap to find most expensive and cheapeast locations
- used a duplicate counter to count how many houses are being sold in each zipcode by counting the number of times a unique houses is shown in a zipcode

<br><br>

### Questions:
- Which price are the most houses being sold and bought at and furthermore which price range has most activity and demand?
- which location/zipcode has most demand?
- What is the relation between sqft_living and price?

### Model


<br><br>


### Methodology

1. **Business Understanding** 
- Based on the Data we want to be able to advise a Real Estate Agency Company which price range and locations are most profitable 
- find the factors which affect prices most and be able to buy houses which are being undersold and resell them.
- find location with most demand so that our business can focus our time and money on those locations with highest probability for profit
   
<br> <br>
2. **Data Understanding**  
Column Names and descriptions for Kings County Data Set
id - unique identified for a house
dateDate - house was sold
price -  is prediction target
bedroomsNumber -  of Bedrooms/House
bathroomsNumber -  of bathrooms/bedrooms
sqft_livingsquare -  footage of the home
sqft_lotsquare -  footage of the lot
floorsTotal -  floors (levels) in house
waterfront - House which has a view to a waterfront
view - Has been viewed
condition - How good the condition is ( Overall )
grade - overall grade given to the housing unit, based on King County grading system
sqft_above - square footage of house apart from basement
sqft_basement - square footage of the basement
yr_built - Built Year
yr_renovated - Year when house was renovated
zipcode - zip
lat - Latitude coordinate
long - Longitude coordinate
sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors
    
   <br><br>
3. **Data Preparation** 
    
  <br><br>
4. **Modelling**
    
<br><br>
5. **Evaluation**
  
<br><br>
6. **Future Tasks**
    
