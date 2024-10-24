**Marvel vs DC Film Franchise(s)**
As there is such a large audience for superheroes, and their stories, one would ask, which is more successful, the Marvel or DC franchise? Most people have a favorite superhero and version of that superhero, which leads one to ask, which is better, Marvel or DC franchise? How do you determine which is better?  We used a dataset to review budgets, profits, character leads, length of films, and Rotten Tomatoes scores to help us determine a universe that is superior.  In Project 1 we are taking a dataset that looks at the Marvel and DC (films only) comparing their budgets, their gross profits worldwide, the length of the film, and their gender lead character and how that affects their Rotten Tomato scores. 

**Methods and techniques:**
Prepare the data for charting/graphing. First, we had to convert columns within the CSV to be integers (float64) instead of objects. 
To determine the Worldwide Box Office Gross by Franchise (in Billions) we had to group the CSV by Francise and then sum the box office gross profits in billions of dollars. 
To determine the Average Budget vs. Average Worldwide Gross for Marvel and DC Movies we aggregated the data by the mean budget and mean box office gross worldwide profits. Then we plotted the graph. 
To determine the distribution of male/female led movies we grouped the movies by the count of male/female-led films. Then grouped the count of those by the total number of films. 
To compare the budget for Male-led and Female-led franchises we first took the data and created a data frame of the male/female led films based on their budgets and plotted the data. 
To determine the average Rotten Tomatoes score by franchise we created a data frame that took the mean scores of the films. Then an average line for the two scores were created to denote that on the bar chart. 
The determination of the budget versus Rotten Tomatoes score was created by using the data frame in a scatter plot. 
To determine the budget by franchise we summed the franchise by the budget column in the dataset. Then we determined the sum of the minutes for each franchise to compare them. 
We used tight layouts, and blue/red color schemes for all charting/graphing. 

**Goals/Desired outcome:**
The goal of this project is to use the dataset to determine if either Marvel or DC is more successful or is superior to each other using budget, gross worldwide box office sums, Rotten Tomatoes score and whether male/female led films are more profitable. 
