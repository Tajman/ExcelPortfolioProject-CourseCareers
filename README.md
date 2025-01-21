# ExcelPortfolioProject-CourseCareers
A MS Excel Project done during the coursework of the Data Analyst Track on Course Careers. 

# Instrutctions and Questions
Assume that budget and gross amounts are in US dollars.

Your workbook should answer the following questions:
* How have gross revenues changed over time?
* How have inflation-adjusted revenues changed over time? 
    * Copy the table from here into the workbook https://www.minneapolisfed.org/about-us/monetary-policy/inflation-calculator/consumer-price-index-1913-. Note: the “Annual Percent Change(rate of inflation)” column is incorrect.
    * Create a new column in the movies worksheet called “CPI of Release Year.” Using a lookup function, create a new column for the CPI for the year the film was released
    * Create a new column in the movies worksheet called “Gross Revenue in 2023 Dollars”. Using the CPI of the release year and the 2023 CPI, calculate the gross revenue in 2023 dollars.
* For the following questions, use sum(gross) / sum(budget) to calculate gross relative to budget.
    * Do movies with higher scores tend to have higher gross relative to budget?
    * Do R rated films tend to have higher gross relative to budget compared with other films? 
    * Do certain genres tend to have higher gross relative to budget?
    * At a high-level, what recommendations can you make about what types of films tend to have the highest gross relative to budget?
 
# My Responses

## Question 1 (How have gross revenues changed over time?)
So over time, the total gross revenues have increased over the years for movies. I first made a pivot table detailing the total gross of movies released by each year. And made a chart illustrating the change over time. But I noticed that in the year 2020 the gross revenue was significantly lower in the whole dataset. So I added the movie release count to the pivot table to show why 2020 had such a low amount, and it showed it had the lowest number of movies released that year. 

## Question 2 (How have inflation-adjusted revenues changed over time?)
Just like with the previous question, the gross revenues increases steadily overtime through the years. But with the increase in gross with 2023 inflation, the amounts have significantly increased causing a higher climb in funds. The top amount previously was about 30 billion, but with inflation, its about 36 billion. And even in the earlier years, some revenues gain at least a 7 million increase because of the 2023 inflation. 

## Question 3 (Do movies with highe scores tend to have higher gross relative to budget?)
In fact yes they do. As shown in the chart, the gross increases at each rate showing a steady climb to the top with higher rates. The highest being at a 8.9 rating. There are some movies that have a a higher score above 8.9 but their relative gross dips significantly from the top. I believe its like that because true (close to) 10/10 movies are few in the pool of movies since people's opinions dont align that close all the time, hence the lower gross. 

## Question 4 (Do R rated films tend to have higher gross relative to budget compared with other films?)
No, R rated films tend to have the least gross relative to budget. Infact, MA-TV rated films have the highest relative budget. But after finding this out, I decided to make another pivot table of the sum of votes for each rating to make sense of why MA-TV rated movies have such a higher gross. Turns out, TV-MA films dont have anywhere near the highest amounts of votes. Its not even in the top 5. But I believe its the case probably because simply TV-MA movies are not seen as frequently as others. 

## Question 5 (Do certain genres tend to have higher gross relative to budget?)
The top three genres from highest gross to least are; Family, Horror, and Animation. For this I made another pivot table putting the movie genres with the total gross relative to budget to see which genres have the higher gross. And to better visualize the amounts, I used a line chart with data points to clearly display which genres have the higher gross. 

## Question 6 (At a high-level, what recommendations can you make about what types of films tend to have the highest gross relative to budget?)
My recommendations for the type of movies that would have a higher gross are MA-TV rated Action movies with a 6 score average (if Not Rated movies were not included). To come to this conclusion, I first created a pivot table showing each genre by row and showing each gross total and average score for each one, filtered by rating. Then created a visual double line and marker chart to see the data points for each genre. (Two vertical value scales for both the gross and score to easily track the lines.) Then I used a slicer to better filter the rating for both the table and chart. But based on my previous findings in the other questions, Action movies have more gross when it is at a MA-TV rating with a 6 average score. Family movies have more of a gross when its PG with a 6.5 average score.

