# Investigate a Dataset of Movies
## 1.Introduction
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.Here I want find Which genres are most popular from year to year and What kinds of properties are associated with movies that have high revenues.
## 2.Data Wrangling
 ###### (1). name of columns[0] is to long ,need to be rename
 ###### (2). dtype of columns[0] is float ,need to be changed to int
 ###### (3). movies.release_year is float ,need to be changed to period
 ###### (4). movies.release_date ,need to be changed to datetime
 ###### (5). movies.revenue_adj, need to be changed to float
 ###### (6). movies.genres,movies.cast,movies.production_companies combineda lot of information together,need to be clean depand on analisys

## 3.Exploratory Data Analysis
### 3.1.1 which genres are the most popular from year to year?
 ###### (1). The sum of diffent genres compared with Mean and Median
 ###### (2). volume of genres from year 1960-2015
 ###### (3). Use popularity to see if a movie is popular with viewers
### 3.2 What kinds of properties are associated with movies that have high revenues?
 ###### (1).explore the relationship between revenue and budget
 ###### (2).explore the relationship between revenue and popularity
 ###### (3).explore the relationship between runtime and revenue
 ###### (4).explore the relationship between invest release_year with revenue
 ###### (5).explore the relationship between properties of high revenue movies
 ###### (6).explory release_year of high revenue movies
 ###### (7).explory runtime of high revenue movies
 ###### (8).explory budget of high revenue movies
## 4.Conclusion
### Three characteristics were found from the analysis of popularity.
 ###### (1). It can be found that the film went through three stages of development from 1960 to 2015. The period of steady development before 1960-1980.
 ###### (2). From 1980 to 2000, during the period of rapid development, Drama and Commedy Rapid development, the main force in the market, meanwhile, action, crime movies have also entered the rapid development at this stage.
 ###### (3). After 2000, it entered a boom period. Action, Adventure, Fatansy, Animation, Thriller, Science Fiction and other types of movies developed rapidly. Competition in the film industry has intensified, and audience preferences have also changed. It is worth noting that Adventure, Action, Science Fiction, Animation, and the proportion of output, popularity index and high-revenue type have all increased rapidly at the same time. Is an emerging film market.
### On the correlation analysis of high-yield and other attributes, runtime, release_year, budget, and genres are selected for analysis. The following problems can be found through analysis:
 ###### (1). Movie revenue is statistically related to runtime, and high-yield movies are 24-28 minutes longer than normal movies.The release year of movies and movie revenues are on the decline overall, but high-revenue movies have appeared since 2002. What does this mean after 2002?There is a large difference in movie revenue in general. Movies with high revenue are extremely high, but movies with low revenue are even lower.
 ###### (2). The budget of a movie is positively related to the income of the movie. The budget of a high-yield movie is definitely higher than the average movie.
 ###### (3). Fast-growing films such as Adventure, Action, Science Fiction, and Animation have a higher percentage of high-revenue movies.
