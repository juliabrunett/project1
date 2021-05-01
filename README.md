# project1
## Group Project: The Movie Database Analysis

**Images Folder:** 
- PNG Images of Analysis

**Output_Files:**
- CSV files of collected API data
- CSV files of merged dataframes

**Data Exploration:**
- Data_Exploration_API.ipynb (Julia)

**Data Cleanup:**
- part2.ipynb (Shante)

**Analysis:** 
- Ratings_vs_Earnings.ipynb (Ratings vs. Revenue) (Sanureet)
- RevenueRatings_vs_Genre.ipynb (Genre Breakdown) (Dana)
- Revenue_vs_Budget.ipynb (Revenue vs Budget) (Vasu)

**Presentation:**
- project_1.pdf

**Overall Analysis:**

*Ratings vs. Revenue*

One analysis we looked into was the relationship between a movie's ratings, and what it ultimately grossed. We used scatter plots to discover what that relationship is, and if there is a significant correlation between the two factors. We looked at the r-values to discover any correlation between 4 different rating websites (The Movie Database, IMDb, Rotten Tomatoes, and Metacritic) and the revenue grossed in the top 20 films of the past 5 years. We found that the r-values for these relationships ranged from about 0.22 to 0.30 (with the highest r-value being between The Movie Database and Revenue). These r-values were greater than zero, suggesting some kind of a relationship, but were not close enough to 1 for us to conclude that ratings and revenue would be able to predict each other well in every scenario. We expected to see a greater and more significant relationship, but concluded that ratings and revenue are related but still vary significantly in multiple scenarios. 

*Budget vs. Revenue*

Another analysis we looked into was the relationship between the budget of a movie and what it ultimately grossed. We expected the relationship to be significant, where for the most part, the budget of a movie could predict how much revenue it would gross. We also used a scatter plot to look overall at the relationship between the budget and the revenue, and found that there is a positive correlation between the two factors. The r-value between these two factors is 0.52, which is significant, but not quite as high as we would've hoped. We also binned the revenue to look at different insights between different revenue categories, and looked at the overall revenue and budgets of the top 5 movies. Additionally, we looked at the revenue increase by year, and found that 2016 had the lowest revenue of its top 20 films compared to the other years.


*Genre Breakdown: Budget vs. Ratings & Revenue*

The final analysis we looked into was the relationship between the budget of a movie and the ratings it received, as well as with the revenue it grossed, and breakdown analysis to look into the differing relationships within each genre. We chose to look into four genres: Action, Adventure, Family, and Science Fiction, and discover if there are differing relationships between the budget and the revenue and the budget and the ratings, by each of the four genres chosen. It was discovered that the ***Adventure*** genre had the most insight, where the r-value of the relationships between the revenue and budget was 0.82. This suggests that the relationship between the budget and the revenue within the Adventure genre is very significant, where they are strongly correlated. 

