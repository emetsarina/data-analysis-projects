# Analysis of the food service in Moscow

## Presentation of the analysis
Presentation: https://drive.google.com/file/d/13W_vLSiF02f3YtWzu0yNM26osy0JwgGd/view?usp=sharing

## Description of the project  
Preparation of a study of the food service in Moscow, search for interesting features and presentation of the results obtained, which in the future will help in choosing a suitable place for investors.  
A dataset with Moscow food service compiled on the basis of data from Yandex Maps and Yandex Business services for the summer of 2022. The information posted in the Yandex Business service could have been added by users or found in publicly available sources. It is purely for reference purposes.  

## Description of the data
File `moscow_places.csv`:
- `name` — the name of the establishments  
- `address` — the address of the establishments 
- `category` — the category of the establishments, for example, "cafe", "pizzeria" or "coffee shop"  
- `hours` — information about working days and hours  
- `lat` — latitude of the geographical point where the establishment is located  
- `lng` — the longitude of the geographical point where the establishment is located  
- `rating` — the rating of the place according to user ratings in Yandex Maps (the highest rating is 5.0)  
- `price` — the category of prices in the establishment, for example, "average", "below average", "above average" and so on  
- `avg_bill` - a string with the average cost of an order as a range, for example:  
-- "Average bill: 1000-1500 ₽";  
-- "The price of a cappuccino cup: 130-220 ₽";  
-- "The price of a glass of beer: 400-600 ₽".  
-- and so on;  
- `middle_avg_bill` - a number with an average bill, which is specified only for values from the avg_bill column starting with the substring "Average bill":  
-- If a price range of two values - the row concludes the median of these two values.  
-- If a price range is a single number — the row concludes this number.  
-- If there is no value or it does not start with "Average bill" - the row concludes nothing.  
- `middle_coffee_cup` - a number with the rating of one cup of cappuccino, which is specified only for values from the avg_bill column starting with the substring "The price of a cappuccino cup":  
-- If a price range of two values - the row concludes the median of these two values.  
-- If a price range is a single number — the row concludes this number.  
-- If there is no value or it does not start with "The price of a cappuccino cup" - the row concludes nothing.  
- `chain` - a number expressed as 0 or 1, which means is the establishment chain or independent:  
-- 0 — the establishment is independet  
-- 1 — the establishment is chain  
- `district` — the administrative district in which the establishment is located, for example, the Central Administrative District  
-`seats` — the number of seats.

## Tools
`Python`, `Pandas`, `Seaborn`, `Plotly`, `Visualisation of the data` 




