## **Overview**

### The purpose of this project is to identify what, if any, factors lead to success of a movie. The sample extracted contains movies from 2010 to 2020 only.
#### [The Movies Data](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) from Kaggle is the source used for this analysis.
---
### **Pulling from the data, the team started with three quesions:**
##### 1. How did movies perform based on genre from 2010 to 2020?
##### 2. Is there a correlation between the budget for the movie and the rating it recieved?
##### 3. Does the rating of a movie directly correlate with the revenue it earns?
---
### **Hypothesis:**
#### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
#### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.
---
## **Analysis**
### **No. 1 : How did movies perform based on genre from 2010 to 2020?**
##### Note: These genres are the "parent" genre of the movie, which we felt would be the best representation of the film's subject matter.

#### From the complete dataset cleaned by Louis and represented by Adam, the **top** five genres are as follows:
  ##### 1. History
  ##### 2. Music
  ##### 3. Documentary
  ##### 4. War
  ##### 5. Drama
---
#### A surprising discovery that leads to more questions. 

##### How many movies in the history genre were factual, rather than based on true events? With history sitting at the top, does this stem from an interest to learn about the past, or was it a cathartic experience for people who have trouble feeling comfortable in a world that was plunged into the digital age?

##### Are the documentaries that made it to the top a reflection of peoples' worries? Furthermore, how many are reliant on the internet either for data or interest of the public? (Thinking of the various diet crazes and nutrition models that were proven wrong and right, and how the internet played a big role in the mass confusion that people experienced with trying to have a balanced diet.)

##### These subjects are likely viewed to be more suitable to a wider age-range than the five lowest rated genres.
---
#### The five **lowest** performing genres:
  ##### 1. Horror
  ##### 2. Comedy
  ##### 3. Thriller
  ##### 4. Action
  ##### 5. Fantasy & Foreign
---
#### Horror, thriller, and comedy genres all have a commonality - they heavily rely on people's tastes. 
##### In general, it is not condusive to our evolution to like being scared. There are likely studies that show a negative connection for the health of people who choose to be scared on a regulary basis. RIP. 

##### Comedy has always been a divisive genre, as people's opinions on what consitutes as funny varies more than other types of entertainment. Everyone likes to laugh, but not everyone finds the same views/remarks/stories funny. It can also be noted that comedy plays a huge role in most movies as the sub-genre.
---

### **No. 2 : Is there a correlation between the budget for the movie and the rating it recieved?**
##### Drawing from the plots, the data reveals a low-grade, insignificant pattern. The highest budgeted film was rated below a 7, while a very low-budget film sits at a rating of 9- the highest in this dataset. While there may be a correlation between budget and rating, it does not consitute causation. From this, we can conclude that there are plenty of other factors that contribute to success, such as the writing, organization, actors, director style, etc.

##### Final answer: No

### **No. 3 : Does the rating of a movie directly correlate with the revenue it earns?**
##### The Movie Rating's v Revenue's plot shows a notable difference in correlation. While the movies are still spread out, there is a discernable trend between the rating it received and the revenue it earned. (People who hear about a good movie are more likely to pay to watch it, after all!) There is still a shroud of points at the low-end of revenue, which could be attributed to marketing and palatability of the content to the masses.

##### Final answer: Soft yes
---
### **Back to our hypothesis!**
#### Null: If budget is not related to movie success (by rating), there will be no correlation between these factors.
#### Alternate: If the budget is directly correlated to movie success, the rating will increase in proportion to the budget.

##### According to our data, we have concluded with the null hypothesis. The R-squared value between these factors is 0.00599181, which does not signify a direct success of ratings strictly due to the budget. 
