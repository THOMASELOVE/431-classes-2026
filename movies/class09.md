# Favorite Movies: Class 09 Breakout Activity (2026-09-22)

## Your Task(s) for Today

After we look at this page together, you'll have about 20 minutes to accomplish these five tasks.

1. Form a group of 3-5 people, ideally including at least person you don't know yet. Come up with a group name that each of you will still remember in a week.
2. One person in your group will report the results of your work using the Google Form found at **INSERT LINK HERE**.
3. As a group, you will identify **two** exploratory questions about films in this sample that could be addressed using the six key variables (`year`, `imdb_genres`, `imdb_ratings`, `imdb_stars`, `length` and `mpa`) listed below.
    - A good question (a) explores relationships involving two or more variables from the data set (b) lets us use data from all (or almost all) of the films and (c) ends with a question mark.
    - As an example that fits at least (a) and (c), we might ask "Do dramas last longer than comedy films?" which could be answered using the `length` and `imdb_genres` variables, although (b) is a problem since some films are not listed as either Drama or Comedy.
    - The current version (dated 2026-09-22) of the movies data is available in our Shared Google Drive folder, or you can [download the Excel version here] **INCLUDE LINK**.
4. Look at this [list of movies](movie_list.md). Alphabetically, what is the first movie (i.e., lowest `mov_id` value) that **all** of the members of your breakout group have seen? 
    - [The form] **INCLUDE URL** asks you to type in that movie's `mov_id` value and name. If there isn't a movie on the list that you've all seen, you'll type in "We couldn't find one."
5. Ensure that your group's reporter has completed [the Google Form] **INCLUDE URL** to report your group's results and has submitted the form successfully (they should receive an email confirmation.)

## The Six Variables We're Focusing On Today

We will use the `movies_2026-09-22` data in the **Favorite Movies** directory in our Shared Drive, which describes 282 films mentioned as "favorites" by students in 431 for 2020-2026. 

There are six variables (`year`, `length`, `imdb_genres`, `imdb_ratings`, `imdb_stars` and `mpa`) that we will focus on today...

Variable | Sample Value | Explanation
:--------: | :------------: | ------------------------------------------------------------------------
**`year`** | 1968 | year movie was released
**`mpa`** | G | Rating by the [Motion Picture Association](https://www.motionpictures.org/); [see below](#about-mpa).
**`length`** | 149 | length of movie (in minutes)
**`imdb_ratings`** | 764,000 | Number of Star Ratings (IMDB)
**`imdb_stars`** | 8.3 | Weighted Average Star Rating (IMDB) <br> between 1.0 (worst) and 10.0 (best)
**`imdb_genres`** | Adventure, Sci-Fi | Movie Genre Categories specified by IMDB <br> (between 1 and 8 genres are listed, [see below](#about-imdb_genres))

The other variables found in `movies_2026-09-22` are...

Variable | Sample Value | Explanation
:--------: | :------------: | ------------------------------------------------------------------------
`mov_id` | M-006 | code (M-001 to M-260): arranges in alphabetical order by title, <br> ignoring starting "The" or "A"
`movie` | 2001: A Space Odyssey | film title according to IMDB
`imdb_link` | - | Web link to IMDB main page for this movie
`list_26` | 0 | # of students in Fall 2025 who selected this movie
`imdb_synopsis` | - | IMDB Movie Synopsis (max. 250 characters)

The **Variable Descriptions and Sources** tab in the Google Sheet has additional information on some of these variables.

## About `mpa`

Across the 282 movies listed by students as their favorite in 2020-2026, each fits in one (and only one) of the 10 **`mpa`** categories listed here:

`mpa` | PG-13 | R | PG | Not Rated | G | Approved | TV-G | TV-14 | TV-MA | TV-PG 
:-----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | ----: | 
Count | 89 | 87 | 72 | 16 | 9 | 2 | 2 | 2 | 2 | 1

## About `imdb_genres`

Across the 282 movies listed by students as their favorite in 2020-2026, 923 genres are listed in **`imdb_genres`**. Each movie has 1-8 genres listed, and 20 different genres are listed. Here are the counts of individual genres for these movies...

Genre | Count | - | Genre | Count | - | Genre | Count | - | Genre | Count 
---------- | ---: | --- |  ---------- | ---: | --- | ---------- | ---: | --- | ---------- | ---:
Drama | 167 |  | Fantasy | 62 | | Animation | 33 | | Horror | 14
Comedy | 113 | | Thriller | 57 | | Mystery | 32 | | War | 12
Adventure | 92 | | Sci-Fi | 53 | | Musical | 19 | | Sport | 8
Romance | 67 | | Family | 48 | | Biography | 17 | | History | 6
Action | 65 | | Crime | 39 | | Music | 17 | | Western | 2

### Other Questions You Might Have

- [Why does IMDB publish Weighted Average Ratings?](https://help.imdb.com/article/imdb/track-movies-tv/weighted-average-ratings/GWT2DSBYVT2F25SK?ref_=ttrt_wtavg#)
- How much missing data is in the key six variables today, across the 282 films?
    - None, unless you treat Not Rated as missing in `mpa` (I'm not saying you should), in which case those 16 values would be "missing".
