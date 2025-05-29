
![Film](https://kimballlibrary.com/wp-content/uploads/2022/06/Movie-Film.jpg)
# Hollywood, Here We Come!
Analysis by Jordan Scriven  

## Business Understanding
Deciding to get into the film industry is a big first step!  It's an exciting new adventure.  Next step is determining what films we'd like to make to be successful!

## Data Understanding
IMDb, the Internet Movie Database, is a website containing all information regarding films, including cast, genres, runtimes, rating and production crew. Starting this new movie studio with a new production crew, we concentrated on the information that we can mimic in our own films - genre and runtimes.

While IMDb records and data can provide instruction on making a movie that audiences love, our company also needs to earn a profit in our new endeavor.  Box Office records for 2010 through 2018 were collected which we will use to accomplish our goal of succeeding in Hollywood.

### Data Preparation and Analysis
After examining all of the information available, we used the Titles in both the IMDb tables and the Box Office data to pool together the information provided by either source. Throught the process, we cleaned up the data by dropping unncessary columns, removing rows that contained missing information and, in the genre column, cleaning up the multi-genre groups.

Because the Box Office data had far fewer records (3,387) than IMDb (nearing 150,000), we first checked to see if there was enough relation between the earnings datapoint in the Box Office data and the average rating from IMDb. Meaning, could we use the rating for those films which we do not have earnings. While the graph showed a slight skew left, the statistic was not enough to do so.

![Total Gross Earnings vs Average Rating](https://github.com/user-attachments/assets/091bdb0d-9ddb-4ca5-98df-e8ecf7545acf)

The data included information on the genre of the movies.  There were many different genres, but we cleaned up the group and concentrated on the top 6 genres, when ranked by sample size.  These 6 genres are Action, Adventure, Comedy, Drama, Romance and Thriller.  After looking at the genres, we concentrated on the runtime of the movies to determine if that had an affect on the rating or earnings.

The data found that both Genre and Runtime had an affect on the Gross Earnings.

![Genre Earnings](https://github.com/user-attachments/assets/6e1bc648-10ba-4ed9-8aed-b6e436036a6f)

![Runtime Earnings](https://github.com/user-attachments/assets/d019b776-0d3c-4123-885e-befad381ceac)

Our graphs show that the Genre of a film made little difference in how the users of IMDb rated them.  But Runtime was an indicator of the Rating.

![Genre Rating](https://github.com/user-attachments/assets/1e42c3d1-7805-4f12-81f7-d90363c85a23)

![Runtime Rating](https://github.com/user-attachments/assets/b4920052-2af0-442d-a6f8-3742cca0681f)

Finally, we generated an ANOVA table to show the probability that the factors we were examining (Genre and Runtime) are influential on the Earnings.  In line with the graphs above, the ANOVA shows that both factors are highly likely to have an influence on Earnings.

## Conclusion

As we open this new movie studio, we have two goals on which we will be concentrating: 1. Make a great movie!  The more our films are adored, the better our reputation and opportunity for growth. 2. Earn money.

This analysis lead to the conclusion that genre and runtime do have influence on the average rating and average earnings.  In order to succeed, we have come to the following recommendations:


*   **All genres are loved** As shown in the charts above, when it comes to ratings within IMDb, genres have litte affect.  Any of the top six most rated genres have IMDb user rates between 6.175 and 6.6, which is a small window.
*   **Adventure makes money** For the good of our shareholders, the greater priority in this movie studio is making a profit, so it is a great thing that the top genres are equally rated.  Wtih that, we can concentrate on creating files in genres that have the highest earnings - Adventure and Action
*   **Watch your runtime** Runtime does have an affect on the gross earnings.  Up to a limit, the profit generally grows as the length of the movie increases.  The movie rating appears to have a similar effect.

### Limitations
An assumption we made on the data was that films with more than one genre listed could be placed into both categories. We double count their gross earnings and ratings in the averages.  But, without keeping the information, we lost too large a part of our data.

### Next Steps
Now that we have an idea of which genres and what runtimes will bring us the highest rating and gross earnings, it's time to start comparing within those groups.  

*   **Categories within genres** Adventure movies make the most money, on average, but are the best adventure movies in the superhero category, coming of age films, etc.
*   **Who do we need on our team** are these specific actors or actresses combinations that bring in more money within each genre?  Or do certain writers create the most beloved films?  And are they worth the cost?

