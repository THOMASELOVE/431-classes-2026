# Results of "Favorite Movies" Breakout on 2026-09-22

## Variables of Interest

- `length` (length of movie)
- `imdb_stars` (weighted average star rating: 1-10)
- `imdb_ratings` (# of users who gave the movie a star rating)
- `imdb_genres` (up to 8 genre categories per movie)
- `mpa` (MPA rating of movie)
- `year` (year movie was released)

## Your Suggested Research Questions 

- Questions *in italics* are taken from your submissions, after I corrected typographical errors.
    - Major problems with genres (`imdb_genres`) are that movies can have more than one genre (and as many as 8), and there are 20 different genres in our sample.
    - MPA ratings (`mpa`), like genres, include multiple categories (really everything other than PG, PG-13 and R) with very few observations.

### Questions involving comparisons across genres

1. *Are there differences in the mean length of films across genres?* (length, imdb_genres)
2. *Do newer movies from the 2000s tend to have more fiction than older movies?* (year, imdb_genres)
3. *What is the average number of IMDB star ratings for each genre of movie?* (imdb_ratings, imdb_genres)
4. *Are comedy movies associated with lower ratings than other genres?* (imdb_stars, imdb_genres)

### Questions involving comparisons across mpa rating groups

1. *Does the MPA movie rating affect how many IMDB ratings it's given?* (mpa, imdb_ratings)
2. *Is there a difference in the weighted average IMDB rating when stratified by MPA rating?* (mpa, imdb_stars)
3. *Does mpa impact to imdb rating?* (mpa, imdb_stars)

### Associations of the movie's length with other quantities

1. *Is the length of the movie (in minutes) associated with the number of star ratings?* (length, imdb_ratings)
2. *Does the length of the movie affect its amount of IMDB stars?* (length, imdb_stars)
3. *Do shorter length films get better IMDB ratings (imdb_stars)?* (length, imdb_stars)
4. *How does the length of a film vary with its year of release?* (length, year)

### Associations of the movie's age or year of release with other quantities

1. *Are low numbers of reviews associated with movies released before IMDB was created (in 1990)?* (year, imdb_ratings)
2. *Are newer movies more frequently rated (imdb_ratings) than older movies?* (year, imdb_ratings)
3. *Do older movies have more ratings?* (year, imdb_ratings)
4. *Has the IMDB rating stars gone down over years?* (year, imdb_stars)
5. *Does year of release affect to imdb_stars?* (year, imdb_stars)

### Association of number of ratings with number of stars

1. *Does a higher number of IMDB ratings positively impact the number of stars for movies?* (imdb_ratings, imdb_stars)
2. *Is there an association between the number of star ratings and the weighted average IMDB rating?* (imdb_ratings, imdb_stars)

## First Movie all of you have seen from [Our List](movies_list.md)

Group | Members | First Movie on [Our List](movies_list.md) <br /> They've All Seen
:----------------: | :---: | :------------------------:
Beavers | 5 | `M-073` Finding Nemo
IMAXers | 5 | `M-073` Finding Nemo
Dr. Love's Fourth Favorite Film | 4 | `M-030` Black Panther, M-030
World alligators | 4 | `M-021` Barbie 
Jupiter's Moons | 4 | `M-015` Avatar
Sasha likes Movies | 5 | `M-015` Avatar
Movie experts | 4 | `M-005` 300
Tropic of Answer | 5 | `M-003` 10 Things I Hate About You

So, is there anyone in the room who has not seen Finding Nemo?
