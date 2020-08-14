#  Kaggle Challenges House-prices-in-USA-(Regression)






## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Datasets Description](#Datasets-Description)
* [Conclusion](#Conclusion)
* [Reference](#Reference)





## Problem Statement <a name="Problem-Statement"></a>

This project is about house pricing competition on Kaggle,  which intends to apply EDA and  machine learning models in order to predict the house pricing for USA Housing dataset by using python .

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.



## Datasets Description <a name="Datasets-Description"></a>

This is the link to the dataset used for this project:

https://www.kaggle.com/c/house-prices-advanced-regression-techniques

|Feature|Type|Dataset|Description|
|---|---|---|---|
|Id|int|train|Id of the house|
|MSSubClass|int|train|Identifies the type of dwelling involved in the sale|
|MSZoning|object|train|Identifies the general zoning classification of the sale|
|LotFrontage|float|train|Linear feet of street connected to property|
|LotArea|int|train|Lot size in square feet|
|Street|object|train|Type of road access to property|
|Alley|object|train|Type of alley access to property|
|LotShape|object|train|General shape of property|
|LandContour|object|train|Flatness of the property|
|Utilities|object|train|Type of utilities available|
|LotConfig|object|train|Lot configuration|
|LandSlope|object|train|Slope of property|
|Neighborhood|object|train|Physical locations within Ames city limits|
|Condition1|object|train|Proximity to various conditions|
|Condition2|object|train|Proximity to various conditions (if more than one is present)|
|BldgType|object|train|Type of dwelling|
|HouseStyle|object|train|Style of dwelling|
|OverallQual|int|train|Rates the overall material and finish of the house|
|OverallCond|int|train|Rates the overall condition of the house|
|YearBuilt|int|train|Original construction date|
|YearRemodAdd|int|train|Remodel date (same as construction date if no remodeling or additions)|
|RoofStyle|object|train|Type of roof|
|RoofMatl|object|train|Roof material|
|Exterior1st|object|train|Exterior covering on house|
|Exterior2nd|object|train|Exterior covering on house (if more than one material)|
|MasVnrType|object|train|Masonry veneer type|
|MasVnrArea|float|train|Masonry veneer area in square feet|
|ExterQual|object|train|Evaluates the quality of the material on the exterior|
|ExterCond|object|train|Evaluates the present condition of the material on the exterior|
|Foundation|object|train|Type of foundation|
|BsmtQual|object|train|Evaluates the height of the basement|
|BsmtCond|object|train|Evaluates the general condition of the basement|
|BsmtExposure|object|train|Refers to walkout or garden level walls|
|BsmtFinType1|object|train|Rating of basement finished area|
|BsmtFinSF1|int|train|Type 1 finished square feet|
|BsmtFinType2|object|train|Rating of basement finished area (if multiple types)|
|BsmtFinSF2|int|train|Type 2 finished square feet|
|BsmtUnfSF|int|train|Unfinished square feet of basement area|
|TotalBsmtSF|int|train|Total square feet of basement area|
|Heating|object|train|Type of heating|
|HeatingQC|object|train|Heating quality and condition|
|CentralAir|object|train|Central air conditioning|
|Electrical|object|train|Electrical system|
|1stFlrSF|int|train|First Floor square feet|
|2ndFlrSF|int|train|Second floor square feet|
|LowQualFinSF|train|df|Low quality finished square feet (all floors)|
|GrLivArea|int|train|Above grade (ground) living area square feet|
|BsmtFullBath|int|train|Basement full bathrooms|
|BsmtHalfBath|int|train|Basement half bathrooms|
|FullBath|int|train|Full bathrooms above grade|
|HalfBath|int|train|Half baths above grade|
|BedroomAbvGr|int|train|Bedrooms above grade (does NOT include basement bedrooms)|
|KitchenAbvGr|int|train|Kitchens above grade|
|KitchenQual|object|train|Kitchen quality|
|TotRmsAbvGrd|int|train|Total rooms above grade (does not include bathrooms)|
|Functional|object|train|Home functionality (Assume typical unless deductions are warranted)|
|Fireplaces|int|train|Number of fireplaces|
|FireplaceQu|object|train|Fireplace quality|
|GarageType|object|train|Garage location|
|GarageYrBlt|float|train|Year garage was built|
|GarageFinish|object|train|Interior finish of the garage|
|GarageCars|int|train|Size of garage in car capacity|
|GarageArea|int|train|Size of garage in square feet|
|GarageQual|object|train|Garage quality|
|GarageCond|object|train|Garage condition|
|PavedDrive|object|train|Paved driveway|
|WoodDeckSF|int|train|Wood deck area in square feet|
|OpenPorchSF|int|train|Open porch area in square feet|
|EnclosedPorch|int|train|Enclosed porch area in square feet|
|3SsnPorch|int|train|Three season porch area in square feet|
|ScreenPorch|int|train|Screen porch area in square feet|
|PoolArea|int|train|Pool area in square feet|
|PoolQC|object|train|Pool quality|
|Fence|object|train|Fence quality|
|MiscFeature|object|train|Miscellaneous feature not covered in other categories|
|MiscVal|int|train|$Value of miscellaneous feature|
|MoSold|int|train|Month Sold (MM)|
|YrSold|int|train|Year Sold (YYYY)|
|SaleType|object|train|Type of sale|
|SaleCondition|object|train|Condition of sale|




## Conclusion <a name="Conclusion"></a>

In conclusion, we used multiple data cleaning and EDA techniques to analyze and visualize our dataset.In the end, we applied multiple machine learning methods in order to predict the Sale Price of the houses in the test data set. The regrission models used were Linear, Ridge, Lasso, KNN, Decision Tree, Random Forest and a few more models. We achieved a good score in Kaggle competition.




## Reference <a name="Reference"></a>

The link bellow is for our Kaggle Challenges House Prices

https://www.kaggle.com/khwlaali/super-dsi7

