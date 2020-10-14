# pandas-challenge

## Heroes of Pymoli

### Challenge details

This challenge entailed analyzing data related to a newly released game: Heroes of Pymoli. Performing the below analyses simulates the preparation of a status report the gaming company would need to help gain insights into how the game can be improved. 

The Python library Pandas was used extensively in this challenge, as dataframes offer an excellent way to view and investigate data.

The analyses include:
* Total count of players
* Purchasing Analysis
    * Number of Unique Items, Average Purchase Price, Total Number of Purchases, Total Revenue
* Gender Demographics
    * Percentage of Male, Female, and Non-disclosed players
* Purchasing Analysis by Gender
    * Purchase Count, Average Purchase Price, Total Purchase Value, Average Purchase Total per Person 
* Age Demographics
    * Purchase Count, Average Purchase Price, Total Purchase Value, Average Purchase Total per Person 
* Top Spenders - top 5 spenders identified, along with:
    * SN, Purchase Count, Average Purchase Price, Total Purchase Value
* Most Popular Items - top 5 items identified, along with:
    * Item ID, Item Name, Purchase Count, Item Price, Total Purchase Value
* Most Profittable Items - top 5 items identified, along with: 
    * Item ID, Item Name, Purchase Count, Item Price, Total Purchase Value

### Data Analysis and Insights

1. Age range 35-39 shows the highest average purchase price ($3.60) and highest average total purchase per person ($4.76). Meanwhile, although the <10 age demographic does not have a large amount of players, they have the second highest average total purchase per person ($4.54) of all the age ranges.

2. While the age range of 20-24 has the greatest number of players, it also has the greatest number of purchases (365) and makes up 46.8% of all purchases. It can also be noted that the number of players correlates positively with the number of purchase per age group. This means that the >40 age range has the least number of players and also the least number of purchases.

3. Unsurprisingly, the most profitable items are all over $4.20, which is significantly higher than the $3.05 average purchase price. However, the top 2 most profitable items (Final Critic and Oathbreaker, Last Hope of the Breaking Storm) are not the most expensive items available, and are still the most profitable items in the game.

### Files Included

* HeroesOfPymoli folder contains the jupyter notebook file with all analyes performed
* Resources folder - contains the csv where all game data is stored
