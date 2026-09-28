# Favorite Movies: Breakout Activity for Class 13

I anticipate this task will be introduced during Class 12 (2026-10-01) and then actually happen in Class 13 (2026-10-06).

## Your Task(s)

You'll have 20-25 minutes to accomplish the following tasks.

1. Form a group of 3-5 people. Come up with a name for your group that each of you will remember at our next class. 
2. One person in your group will report the results of your work using the Google Form at <https://tinyurl.com/431-2026-movies-class-13>. Try to have someone who hasn't done this for prior work do this, so I can spread around the credit.
3. As a group, you will identify **two new variables** (one **categorical** and one **quantitative**) available on the internet (from sources other than IMDB) that could be added to the data to expand on what could be studied here in an interesting way. For each variable, we're hoping you will (a) identify a URL on the internet where those data seem to be available and (b) identify a **meaningful exploratory question** that incorporates that variable, along with at least one of the variables we have available in the existing data base. 
    - A current list of variables is found at the bottom of this page, and is also in the "Variable Descriptions" tab of the **movies_2026-10-01** Google Sheet in the Favorite Movies subfolder of our Shared Drive. All of those variables come from [IMDB](https://www.imdb.com/) or myself.
    - **Each** of the two new variables you select should come from a source other than [IMDB](https://www.imdb.com/).
        - Some sources students have used in the past include: [Rotten Tomatoes](https://www.rottentomatoes.com/), [Flickchart](https://www.flickchart.com/), [Bechdel Test Movie List](https://bechdeltest.com/), [Does The Dog Die?](https://www.doesthedogdie.com/), [Kids in Mind](https://kids-in-mind.com/), [Oracle of Bacon](https://oracleofbacon.org/), [The-Numbers](https://www.the-numbers.com/), [Metacritic](https://www.metacritic.com/), [RogerEbert](https://www.rogerebert.com/), [Movielens](https://movielens.org/), [Filmcrave](https://www.filmcrave.com/), [Letterboxd](https://letterboxd.com/welcome/) and [Open Movie Database](https://omdbapi.com/), but please don't feel obliged to stick to these options.
    - Your first variable should be **categorical** (with 2-10 mutually exclusive and collectively exhaustive levels, and without a lot of missing data.) 
        - An example (that you shouldn't use, since I have it already) would be the Motion Picture Association's Rating (G, PG, PG13, R, etc.) which is also available on IMDB's page for the film.
        - Another example you shouldn't use is anything to do with the genre of the movie. We'll go with what we have from IMDB.
        - The categories in your suggested variable can be either ordinal or nominal.
    - The other variable you suggest should be **quantitative**, so that it takes values across a range of numerical results, and has units of measurement. 
        - An example (that you shouldn't use, since I have it already) would be the percentage of raters on IMDB that rated the film at the maximum level (10 stars) which is a percentage ranging from 0% to 100%. This is available by clicking on the number of people who rated the film on the main IMDB page.
        - In this work, we'll require a quantitative variable to be any quantity that has at minimum 11 different observed values in our set of films. Eleven is too small a count, really, to declare something "quantitative" in practice, but we'll make the best of it.
4. Ensure that your group's reporter has completed [the Google Form](https://tinyurl.com/431-2026-movies-class-13) to report your group's response and has submitted the form successfully (they should receive an email confirmation.)

## Variables Included In `movies_2026-10-01`

The current codebook for the data set is listed below. Additional information is in the *Variable Descriptions and Sources* tab in the **movies_2026-10-01** sheet on our Shared Drive. The data are also available in this [movies_2026-10-01.xlsx](movies_2026-10-01.xlsx) Excel file.

Variable | Description
:------------ | :-----------------------------------------------------------------------------------------------------
mov_id | Code # (Mxxx) - alphabetical with #s first; sequels after originals
movie | Name of Movie
year | Year Movie was Released
mpa | Motion Picture Association rating
length | Length of Movie (minutes)
imdb_ratings | # of IMDB public ratings as of 2026-09
imdb_stars | # of stars (1-10) in IMDB public rating as of 2026-09
imdb_pct10 | % of 10-star public ratings in IMDB as of 2026-09
metascore | # of critic reviews gathered at IMDB as of 2026-09
critic_revs | # of critic reviews gathered at IMDB as of 2026-09
oscars | # of Oscar (Academy Award) wins according to IMDB
awards | # of awards (wins) according to IMDB as of 2026-09
imdb_genres | Movie's list of Genres (up to 10) as identified by IMDB
genre_count | Number of Genres identified by IMDB
director | Name of director(s) of movie
star_1 | Name of first listed actor (star) in movie
gen_1 | Gender of star_1 (M or F) in movie
star_2 | Name of second listed actor (star) in movie
gen_2 | Gender of star_2 (M or F) in movie
star_3 | Name of third listed actor (star) in movie
gen_3 | Gender of star_3 (M or F) in movie
origin | Country (Countries) of Origin
lang_1 | Primary language used in the Movie
budget | Estimated Budget via IMDB (in $)
gross_northA | Gross Revenue in US and Canada ($)
gross_world | Gross Revenue Worldwide ($)
pct_northA | % of gross_world from US and Canada
box_off_m | Box Office Multiple
color | Color or Black and White movie
imdb_link | Link to IMDB public page for movie
imdb_id | IMDB movie ID # 
dr_love | Has Dr. Love seen this movie? (Yes or No) as of 2026-09-01
mentions | # of times movie mentioned by 431 students in 2020-2026
list_20 | # of 431 students who mentioned this movie in Fall 2020
list_21 | # of 431 students who mentioned this movie in Fall 2021
list_22 | # of 431 students who mentioned this movie in Fall 2022
list_23 | # of 431 students who mentioned this movie in Fall 2023
list_24 | # of 431 students who mentioned this movie in Fall 2024
list_25 | # of 431 students who mentioned this movie in Fall 2025
list_26 | # of 431 students who mentioned this movie in Fall 2026
imdb_synopsis | Synopsis from IMDB Front Page


