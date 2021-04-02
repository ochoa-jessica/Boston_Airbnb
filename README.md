# Boston_Airbnb_EDA

## Project Motivation
For this demo, I have used the open data source compiled by Inside Airbnb on 10 June 2020 to analyze Boston Airbnb Dataset by performing EDA based on three criteria's - a) Location - What regions do you have more choice or are more likely to stay in Boston Airbnb?; b) Room Type - What types of rooms are most popular for stay?; c) Price - What are the important features to influence the price? Could you predict the price of Boston Airbnb?

## Boston Airbnb Dataset
Consists of 3440 listings and 16 features of Airbnb across 25 neighborhoods of Boston.

## EDA
![Paired relations](EDA/PairPlots.png)
### Reviewing paired relations among nine numerical features
**Latitude:** From South 42.25 to North 42.40, the number of listings are increasing.
**Longitude:** From West -71.15 to East -71.00, the number of listings for Boston Airbnb increases.
**The Number_of_Reviews and Reviews_Per_Month** are positively correlated.

![Spearman Correlation Among 9 Features](EDA/Spearman_Correlation_9_Features.png)
### Reviewing Spearman correlation heatmap to find any correlation among nine numerical features
**Latitude** is positively correlated with price(r=0.31) and longitude(r=0.30).
**The number of reviews and review per month** are positively correlated(r=0.44).
**Availability 365 and calculated host listings count** are positively correlated(r=0.25).

### Location - What regions do you have more choices or will you more likely to stay in Boston Airbnb?
![25 Neighborhoods Across Boston](EDA/25_Neighborhoods_Boston.png)
<p>The number of listings of Airbnb across 25 Neighborhoods in Boston.</p>

![Top Five Neighborhoods Across Boston](EDA/Top_Five_Neighborhoods_Boston.png)
<p>Top five neighborhood locations in Boston that are likely to have higher chance of us finding Airbnb.</p>

![Dorchester one among other 25 neighborhoods leading in Boston](EDA/Dorchester_Leading.png)
<p>Remarkably, Dorchester has an easily higher proportion of Airbnb compared to other neighborhoods, at 12%.</p>

![Distribution of Airbnb across Boston](EDA/Density_Plot.png)
<p>The distribution of Airbnb across Boston, the brightest are has the highest amount of Airbnb.</p>

### Room Type - What types of rooms are most popular to stay?
![Room Types that are popular for stay](EDA/Room_Type.png)
<p>Entire home/apt and Private room are among the available choices while considering the number of listings.</p>

![Airbnb listings available for 365 days](EDA/Availability_365.png)
<p>There about 425 Airbnb Listing available in all 365 days/</p>

![Average number of nights by room type](EDA/Average_Nights.png)
<p>Travelers tend to stay longer in shared rooms than in private rooms and entire home/apt.</p>

![Average reviews by room type](EDA/Average_Reviews.png)
![Average reviews per month of nights by room type](EDA/Average_Reviews_Per_Month.png)
<p>Private room and Entire home/apt have a higher average number of reviews than Shared rooms and Hotel rooms.</p>

![Average days of availability by room type](EDA/Average_Days.png)
<p>Entire home/apt is one of the popular choices to consider in terms of availability majority of the time as Private and Shared rooms have lesser availability.</p>

![Average days of availability by room type](EDA/Spearman_Correlation_11.png)
<p>After dealing with outliers and removing of rows with price above $500, excluding minor room types, we've a spearman heat correlation of 11 features.</p>

### Price - What are the important features to influence price? Could you predict the price of Boston Airbnb?
<p> The average price by private room is about $81.22, while the average price by the entire home/apt is much higher at about $189.38.</p>





