# surfs_up
Module 9: Advanced Data Storage and Retrieval

## Overview
- We have been working on potentially opening up a surf and ice cream shop on the island of Oahu in Hawaii. W. Avy is willing to invest as he has a passion for surfing and ice cream but he needs to have easy access to weather statistics as he has tried to open a surf and ice cream shop before but didn't factor in weather. We have been able to use Flask to display certain points of weather data on the island from the past year (August 23, 2016 to August 23, 2017). 
- We have successfully created the Flask app to display the temperatures for the dates along with the min, average, and max temperatures for a certain given range inputed by the user. Now W. Avy wants specific temperature trends for the months of June and December before opening a surf and ice cream shop. 
## Results
June vs December Temperature Summary Stats

![june_temps_summary](https://user-images.githubusercontent.com/79118630/115973760-7ded2a80-a525-11eb-9599-208e582a6533.png)  ![december_temps_summary](https://user-images.githubusercontent.com/79118630/115973762-82b1de80-a525-11eb-973b-88612f6532c3.png)

- June has 1700 temperature recordings and December has 1517 temperature recordings. This shouldn't come as a big problem since both have many plenty recordings. However, this could possibly mean that there has been an error in entering the data or that December is observed much less.
- June has a min of 64°F, an average of 74.9°F and a max of 85°F ; December has a min of 56°F, an average of 71°F and a max of 83°F. Since June is in the summer and December is in the winter in Hawaii, this is not a surprise that June has overall higher temperatures.
- Another result that should be noted is that in June, the IQR is between 73°F and 77°F ; and in December, the IQR is between 69°F and 74°F. The actually range differences are 3 and 4, this shows that June even with a min of 64°F, 50% of the tiime the weather stays above 70°F. 
## Summary
### Summary of Results
- It was probably expected for the results to have higher temperatures in June than December because of the seasons. It is also important to note that there isn't a tremendous diffrence between the two, showing that it typically stays fairly warm in Hawaii, this is due to its closeness to the equator. Opening a surf and ice cream shop isn't a bad idea because of the temperature allowing for year long surfing and since it stays fairly warm. However, both months have means that are under 75°F, and in fact, in June in never gets above 85°F (according to the stats). So is it really a good idea to include an ice cream shop in the surf shop if the weather barely goes above 80°F in June? 
### Additional queries
#### June and Dec. by Year
- Another query I would run would be to group the data by years, tracking to see if their is a trend with the temperature by year. We can then display the data with a line graph. This can be helpful in seeing if it is worth investing in an ice cream shop because it is steadily getting warmer by the year, and it is also helpful to raise awareness as climate change is a growing issue.
- Another query would be to include precipitation in the summary statistics. If there is heavy precipitation during June, it wont really matter what the temperature is as it is a safety hazard to surf during storms, and it isn't fun to eat ice cream during storms. December is already a struggling month with lower temperatures, so if there is heavy precipitation then, the store will struggle. 
