## Overview

### [The Movies Data from Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) is the source used for this analysis.
#### The purpose of this project is to identify what, if any, factors lead to success of a movie.
##### Disclaimer: In order to glean meaningful conclusions, data with missing values were cut from the final dataset. While the original data includes more than 14,000 rows, it was narrowed to around 1,600 rows for the team to use it effectively.
---
### Pulling from the data, the team started with three quesions:
##### 1. How did movies perform based on genre from 2010 to 2020?
##### 2. Is there a correlation between the budget for the movie and the rating it recieved?
##### 3. Does the rating of a movie directly correlate with the revenue it earns?
---
### Hypothesis:
#### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
#### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.
---
## Analysis
### No. 1 : How did movies perform based on genre from 2010 to 2020?
##### Note: These genres are the "parent" genre of the movie, which we felt would be the best representation of the film's subject matter.
#### Americans were more interested in learning new things than would likely be hypothesized by the general public! Looking to the past and what surrounds us as we have become more and more detached from the world as it was pre-internet is a delightful discovery.

#### From the complete dataset cleaned by Louis and represented by Adam, the top five genres are as follows:
  ##### 1. History
  ##### 2. Music
  ##### 3. Documentary
  ##### 4. War
  ##### 5. Drama

#### Americans were more interested in learning new things than would likely be hypothesized by the general public! Looking to the past and what surrounds us as we have become more and more detached from the world as it was pre-internet is a delightful discovery.

#### The five lowest performing genres:
  ##### 1. Horror
  ##### 2. Comedy
  ##### 3. Thriller
  ##### 4. Action
  ##### 5. Fantasy & Foreign

#### Horror, thriller, and comedy genres all have a commonality - they heavily rely on people's tastes. 
##### In general, it is not condusive to our evolution to like being scared. There are likely studies that show a negative connection for the health of people who choose to be scared on a regulary basis. RIP. 
##### Comedy has always been a divisive genre, as people's opinions on what consitutes as funny varies more than other types of entertainment. Everyone likes to laugh, but not everyone finds the same views/remarks/stories funny.


### No. 2 : Is there a correlation between the budget for the movie and the rating it recieved?
##### Drawing from the plots, the data reveals a low-grade, insignificant pattern. The highest budgeted film was rated below a 7, while a very low-budget film sits at a rating of 9- the highest in this dataset. While there may be a correlation between budget and rating, it does not consitute causation. From this, we can conclude that there are plenty of other factors that contribute to success, such as the writing, organization, actors, director style, etc.

##### Final answer: No

### No. 3 : Does the rating of a movie directly correlate with the revenue it earns?
##### The Movie Rating's v Revenue's plot shows a notable difference in correlation. While the movies are still spread out, there is a discernable trend between the rating it received and the revenue it earned. (People who hear about a good movie are more likely to pay to watch it, after all!) There is still a shroud of points at the low-end of revenue, which could be attributed to marketing and palatability of the content to the masses.

##### Final answer: Soft yes
---
### Back to our hypothesis!
#### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
#### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.
##### According to our data, we have concluded with the null hypothesis. The R-squared value between these factors is 0.00599181, which does not signify a direct success of ratings strictly due to the budget. 
