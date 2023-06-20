# **Overview**

### The purpose of this project is to identify what, if any, quantifiable factors lead to success of a movie. The sample extracted contains movies from 2010 to 2020 only.
#### [The Movies Data](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) from Kaggle is the source used for this analysis.
---
### **Pulling from the data, the team started with three quesions:**
##### 1. How did movies perform based on genre from 2010 to 2020?
##### 2. Is there a correlation between the budget for the movie and the rating it recieved?
##### 3. Does the rating of a movie directly correlate with the revenue it earns?
---
# **Hypothesis:**
### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.
---
# **Analysis**
## **No. 1 : How did movies perform based on genre from 2010 to 2020?**
##### Note: These genres are the "parent" genre of the movie, which we felt would be the best representation of the film's subject matter.

### From the complete dataset cleaned by Louis and represented by Adam, the **top** five genres are as follows:
  ##### 1. History
  ##### 2. Music
  ##### 3. Documentary
  ##### 4. War
  ##### 5. Drama
---
##### A surprising discovery that leads to more questions. 
##### How many movies in the history genre were factual, rather than based on true events? With history sitting at the top, does this stem from an interest to learn about the past, or was it a cathartic experience for people who have trouble feeling comfortable in a world that was plunged into the digital age?

##### Are the documentaries that made it to the top a reflection of peoples' worries? Furthermore, how many are reliant on the internet either for data or interest of the public? (Thinking of the various diet crazes and nutrition models that were proven right or wrong, and how the internet plays a big role in the mass confusion that people experience with trying to have a balanced diet.)

#### Questions aside, historical movies typically include strong performances partnered with rich storytelling. It connects us to the past and naturally triggers reflection on the changes - good or bad - that have taken place. These subjects are likely to be viewed as more suitable to a wider age-range than the five lowest rated genres.
---
#### The five **lowest** performing genres:
  ##### 1. Horror
  ##### 2. Comedy
  ##### 3. Thriller
  ##### 4. Action
  ##### 5. Fantasy & Foreign
---
#### Horror, thriller, and comedy genres all have a commonality - they heavily rely on people's tastes. 
##### In general, it is not condusive to our evolution to like being scared. There are likely studies that show a negative connection for the health of people who choose to be scared on a regulary basis. This content is also heavily peddled as a reactionary experience, which led to lack of originality and quality.

##### Comedy has always been a divisive genre, as people's opinions on what consitutes as funny varies more than other types of entertainment. Everyone likes to laugh, but not everyone finds the same views/remarks/stories funny. It can also be noted that comedy plays a huge role in most movies as the sub-genre, rather than the main subject matter of the film.
---

## **No. 2 : Is there a correlation between the budget for the movie and the rating it recieved?**
#### Drawing from the Movie Rating v Budget, the data reveals an insignificant pattern with an R-squared value of 0.00599. The highest budgeted film was rated below a 7, while a very low-budget film sits at a rating of 9- the highest in this dataset. While there may be a correlation between budget and rating, it does not consitute causation. From this, we can conclude that there are plenty of other factors that contribute to success, such as the writing, organization, actors, director style, etc.

##### Final answer: No

## **No. 3 : Does the rating of a movie directly correlate with the revenue it earns?**
#### The Movie Ratings v Revenues plot shows a notable difference in correlation to the Genres v Revenues plot. For the sake of having more points to ponder, the former chart mentioned will be used for the analysis of this question. 

#### While the movies are still spread out, there is a minor trend between the rating it received and the revenue it earned. (People who hear about a good movie are more likely to pay to watch it, after all!) There is still a shroud of points at the low-end of revenue, which could be attributed to marketing and palatability of the content to the masses and therefore a smaller sample of people actively reviewing the movie. Action movies were successful in regards to revenue earnings, which is likely due to the rise of technology making the impossible possible. Family oriented films remained consistent in their earnings throughout this period. Critically-acclaimed movies earned more, while action movies earnings did not depend on a high rating to be profitable.

#### The R-squared value for these variables is 0.04158, indicating that there is not a strong correlation enough between these factors to conclude this to be a major factor in movie success.

##### Final answer: No
---
## **Back to our hypothesis!**
#### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
#### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.

##### According to our data, we have concluded that the null hypothesis is accurate. The R-squared value between these factors is 0.00599, which does not signify direct success of ratings strictly due to the budget.
