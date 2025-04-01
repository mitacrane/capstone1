# Capstone 1
[![Open In Colab](https://colab.research.google.com/assets/colab-
badge.svg)](https://github.com/mitacrane/capstone1.ipynb)
## Mita Crane

# Data summary
#The dataset includes data for property sales in Washington state in 2014, 
#likely derived from data published by the Washington Center for Real Estate Research.
#The data includes property sale date; price; year built and renovated; number of bedrooms,
#bathrooms, and floors; square footage of the living area and the lot; ratings of the property’s 
#view and condition; whether the property faces a waterfront; the square footage of the living area above-ground,
#square footage of the basement; address, city, zipcode, and country. The data for property sales ranges from May 2014 to July 2014. 
#The dataset contains numerical data, both discrete and continuous, ordinal and nominal categorical data, and binary data. 

# Summary Statistics
#Average price is $553,063 (range: $0-$26.59M) with extreme right-skew (24.76),
#indicating mostly moderate-priced homes with few luxury properties. Typical 
#homes have 3 bedrooms, 2 bathrooms, 2,144 sq ft living space, and 14,698 sq ft lots.
#Construction dates range from 1900-2014 (median: 1976). Premium features are scarce—only
#0.75% have waterfront access. Property condition averages 3.45/5, and price per square 
#foot averages $265.84. The dataset shows high quality with no missing values.


# Descriptive statistics
##The price-related visualizations reveal key patterns about home valuations. The 
#histogram of house prices shows a strong positive skew, with most properties
#concentrated in the lower to middle price ranges and a long tail of high-priced 
#properties, typical of real estate markets where luxury properties command significant 
#premiums. The boxplot identifies several significant outliers in the price distribution, 
#with a few properties valued above $10 million, and at least one property approaching 
#$30 million - these luxury properties are statistical outliers but represent an important
#segment of the market. The boxplot by city shows substantial variation in median prices
#across the top 5 cities, with Bellevue appearing to have both the highest median prices
#and the most expensive outlier properties, while Kent shows lower median prices with fewer 
#outliers. Seattle and Redmond also have high median prices, reflecting their desirable 
#locations. The scatter plot shows a positive relationship between living area and price, 
#though with considerable variability, suggesting other factors significantly influence 
#pricing beyond just size.
#The boxplot shows that properties in better condition (4-5 rating) command higher median 
#prices, with condition 4 properties showing the widest price range and some of the 
#highest-priced outliers, confirming the value of property condition in determining market
#value. The relationship between bedrooms and price isn't strictly linear - while 3-bedroom 
#homes generally cost more than 2-bedroom homes, the highest-priced outliers appear in the 
#3-bedroom category rather than in homes with more bedrooms, suggesting that other factors 
#(location, quality, lot size) may be more important than simply maximizing bedroom count.

# Correlation statistics
##Waterfront has a positive correlation with price (0.13) and view (0.36), confirming that 
#waterfront properties command a premium and tend to have better views. The year built shows 
#moderate positive correlations with bathrooms (0.47) and floors (0.47), indicating newer 
#homes tend to have more bathrooms and more floors. Interestingly, yr_built has a weak 
#correlation with price (0.03), suggesting that age alone isn't a strong driver of price. 
#Year renovated shows negative correlations with most features, including a -0.32 correlation
#with year built, which makes sense as older homes are more likely to be
#renovated than newer ones. However, renovations don't show a strong
#correlation with price (only -0.03). Surprisingly, sqft_lot has a very weak
#correlation with price (0.05), suggesting that the size of the land isn't as
#important as the size of the home in determining value in this market.
