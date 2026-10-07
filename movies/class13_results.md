# Suggested Variables from Class 13 Breakout Session

## Categorical Variables

Here are the categorical variables you suggested, along with *lightly edited* versions of the exploratory questions you created for them...

Group | Categorical Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
Crunchy Grapes | [Bechdel-Wallace Test](https://bechdeltest.com/)  | Do movies that pass the Bechdel-Wallace test[^1] have a higher number of stars on IMDB?
Tropic of Answer | [Bechdel-Wallace Test](https://bechdeltest.com/) | Is Dr. Love more likely to have seen a movie if it passes the Bechdel-Wallace test?
The Cinematics | [Aspect Ratio](https://www.rottentomatoes.com/)[^2] | Do movies with higher aspect ratios cost more money to make?
The Cinematics | [Streaming Platform](https://www.themoviedb.org/movie/)[^3] | Which streaming platform is most likely to stream movies that are dramas?
SashaCNRlikemovies | [Available to Stream](https://www.justwatch.com/)[^4] | Are movies with higher star ratings on IMDB more likely to be streamable?
SashaCNRlikemovies | [Roger Ebert rating](https://www.rogerebert.com/reviews)[^5] | Do the movies Dr. Love has seen have generally higher star ratings from Roger Ebert?
Beavers | [Freshness](https://www.rottentomatoes.com/) | Do movies with better freshness ratings[^6] on Rotten Tomatoes have a higher number of stars on IMDB?
EMRG | [Kids in Mind Language Score](https://kids-in-mind.com/)[^7] | Do movies with language scores 5 and greater tend to have a higher percentage of the gross revenue from North America[^8]?
Summer Blockbuster | [Main Character Dies](https://www.doesthedogdie.com/) | Do movies have higher numbers of IMDB reviews if the main character dies?
Summer Blockbuster | [Bacon Index](https://oracleofbacon.org/movielinks.php)[^9] | How many degrees of separation are there between the movie's first-billed star and Kevin Bacon?

- Unfortunately, the **World Gators**[^10] and **Never Say NO Movie**[^11] groups didn't follow the instructions, and suggested variables that were (a) on IMDB and/or (b) already in the data set. We will consider adding the month in which the movie was released in the US to the data.

## Quantitative Variables

Here are the quantitative variables you suggested, along with *lightly edited* versions of the exploratory questions you created for them...

Group | Quantitative Variable | Exploratory Question
:----------: | :-----------------: | :-----------------------------------------------------------------------------------
Crunchy Grapes | [Rotten Tomatoes Popcornmeter](https://www.rottentomatoes.com/)[^12] | Do movies with male star_1's have popcornmeter ratings that exceed those of movies with female star_1s?
Beavers | [Average Shot Length](https://cinemetrics.uchicago.edu/database) | What is the association between movie genre[^13] and average shot length?
EMRG | [Number of Theaters](boxofficemojo.com)[^14] | Is the number of domestic theaters a movie was released in lower in non-US countries?
Dolphin Whale | [Weeks Run in Theaters](https://www.the-numbers.com/) | How strongly associated are the age of the movies and how long it ran in theaters?
Tropic of Answer | [Female Dialogue Percentage](https://pudding.cool/2017/03/film-dialogue/)[^15] | Are certain movie genres (which?) associated with higher percentages of dialogue spoken by women?

- Unfortunately, the **World Gators** group didn't follow the instructions, and again suggested a variable that was on IMDB (opening weekend revenue).
- The **Never Say NO movie** group suggested first day gross revenue in the US and Canada, from Wikipedia, which is only available for a very small fraction of movies.

### Notes

[^1]: Here is a [video explaining the Bechdel-Wallace test](https://feministfrequency.com/video/the-bechdel-test-for-women-in-movies/). Bechdel-Wallace scores range from 0 to 3, and are a count of how many of these standards are met by the movie: 1. It has to have at least two named women in it. 2. Who talk to each other 3. About something besides a man. A passing score is 3, anything less doesn't pass the test.

[^2]: The aspect ratio is the ratio of width to height used when filming the movie. This isn't actually a quantitative variable as there are only a few options. Ostensibly this information is on the bottom of the page for a movie on Rotten Tomatoes, but in a random sample of five movies from our list, I didn't find it there even once. It's sometimes listed on IMDB in the technical specifications section.

[^3]: Ostensibly, if the movie is streaming, the streaming platform will appear at the bottom of the movie poster image, but this leaves the issues of accuracy and of what to do when the movie is available for purchase, but not as part of a streaming service.

[^4]: What do we do when the movie is available for purchase on a site like Amazon or Apple or Google TV, but not as part of the regular offerings of a streaming service?

[^5]: You listed Roger Ebert ratings as a quantity in your response, but it's a categorical variable with possible values between 0 and 4 stars, including half-stars, so that's 9 (ordered) categories.

[^6]: A movie is listed on Rotten Tomatoes as "not fresh" if less than 60% of its reviews are positive, as "fresh" if 60-75% of the reviews are positive, and as "certified fresh" if more than 75% of reviews are positive.

[^7]: The Kids in Mind Language rating is a 1 to 10 rating, with higher ratings indicating more "troubling" language.

[^8]: World wide revenue includes the US and Canada, so your original question wouldn't work.

[^9]: This Bacon Score count is specific to a movie star (it's measured at the actor level, not the movie level) which is a serious problem. Also, it's a count, which is always (in my experience) between 1 and 6, so it's not actually a quantitative variable.

[^10]: Your proposed research question was "Movies with English as the predominant language are significantly more likely to be nominated for and win major Academy Award categories (such as Best Picture) than films with non-English as the predominant language." which is a problem in the following ways: (1) It's not a question. (2) It focuses on statistical significance - don't do that, and (3) the "new" category you propose actually "did the movie win a major Academy Award" when what we have is "how many Academy Awards did the movie win" and not "what is the predominant language" which is already in our data set. The problem there is "what counts as a major Academy Award?"

[^11]: You proposed identifying a season when the movie was released based on the month from the release data on IMDB. The task was to find a non-IMDB variable, so that's an issue, but you also didn't provide any suggestion about how to define the seasons of interest.

[^12]: The "popcorn-o-meter" at Rotten Tomatoes describes the % of positive reviews from visitors to the site, rather than from critics. In that sense, it really doesn't being a lot of new information beyond what we already see from IMDB, but OK.

[^13]: Movies overlap in terms of genre (that is, a movie can have more than one genre) and there are [20 different genres](https://github.com/THOMASELOVE/431-classes-2026/blob/main/movies/categories.md) represented. How would you operationalize a relevant question here?

[^14]: Number of theaters the movie was released in 5 days following domestic release, ostensibly available at [boxofficemojo](https://www.boxofficemojo.com/). But your question suggests that this should somehow be gathered for non-US releases, which isn't actually available.

[^15]: The website providing this information was from 2017 and only includes 2000 movies, so it cannot possibly include many of the movies on our list (including all of those since 2017), which is a real shame.
