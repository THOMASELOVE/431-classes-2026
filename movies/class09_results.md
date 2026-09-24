# Results of "Favorite Movies" Breakout on 2026-09-22

## Variables of Interest

- `length` (length of movie)
- `imdb_stars` (weighted average star rating: 1-10)
- `imdb_ratings` (# of users who gave the movie a star rating)
- `imdb_genres` (up to 8 genre categories per movie)
- `mpa` (MPA rating of movie)
- `year` (year movie was released)

## Your Research Questions and My Efforts to Clean Them Up

- Dr. Love's suggested versions of your questions are **shown in bold**.
- Questions *in italics* are taken from your submissions, after I corrected typographical errors.
 
### Questions involving comparisons across mpa rating groups

- Warning: MPA ratings (`mpa`) include [multiple categories](categories.md) (really everything other than PG, PG-13 and R) with very few observations.

TEL suggests: **How strong is the association of a movie's MPA rating with its average IMDB rating?** or maybe **Which MPA ratings have higher average IMDB ratings?** (`imdb_stars`, `mpa`)
- *Is there a difference in the weighted average IMDB rating when stratified by MPA rating?* (How would you do the stratification? Include all options, or just a few?)
- *Does mpa impact to imdb rating?* (There are some problems with grammar here, but also we want to avoid a cause and effect issue in an exploratory question.)

TEL suggests: **How strong is the association of a movie's MPA rating with the number of IMDB ratings it has received?** (`imdb_ratings`, `mpa`)
- *Does the MPA movie rating affect how many IMDB ratings it's given?* (Again, avoiding cause and effect, and there's always some relationship.)

### Associations of the movie's length with other quantities

TEL suggests: **How well can we predict a movie's average IMDB rating using its length?** (`imdb_stars`, `length`)
- *Does the length of the movie affect its amount of IMDB stars?* (This implies a cause-and-effect relationship, which, frankly, we won't be able to assess.)
- *Do shorter length films get better IMDB ratings (imdb_stars)?* (What would your cutoff for "shorter length" films be?)

TEL suggests: **Are more recent films longer?** (`year`, `length`)
- *How does the length of a film vary with its year of release?* (Yours may be fine, too. Mine has an issue with identifying what we mean by more recent.)

TEL suggests: **Do longer movies have more ratings on IMDB?** (`imdb_stars`, `year`)
- *Is the length of the movie (in minutes) associated with the number of star ratings?*

### Associations of the movie's age or year of release with other quantities

TEL suggests: **Do older movies have more IMDB ratings?** (`year`, `imdb_ratings`)
- *Are newer movies more frequently rated (imdb_ratings) than older movies?* (Usual problem with how do you operationalize older and newer.)
- *Do older movies have more ratings?*
- *Are low numbers of reviews associated with movies released before IMDB was created (in 1990)?* (IMDB was founded as a Usenet post in 1990.)

TEL suggests: **Do older movies have higher weighted average star ratings on IMDB?** (`imdb_stars`, `year`)
- *Has the IMDB rating stars gone down over years?* (You need a "the" between over and years.)
- *Does year of release affect to imdb_stars?* (Some serious grammatical problems here - not sure I've captured what you're interested in.)

### Association of number of ratings with number of stars

TEL suggests: **How strong is the association between how often a movie is rated on IMDB and its number of stars?** (`imdb_stars`, `imdb_ratings`)
- *Does a higher number of IMDB ratings positively impact the number of stars for movies?* (What does positively impact mean? What's your cutoff for "higher number"?)
- *Is there an association between the number of star ratings and the weighted average IMDB rating?* (Every set of quantities is correlated with every other set of quantities with the same number of observations, and thus has some kind of association, even if that correlation turns out to be zero.)

### Questions involving comparisons across genres

- Warning: Major problems with genres (`imdb_genres`) include that movies [can have more than one genre](categories.md) (and as many as 8), and there are [20 different genres](categories.md) in our sample.

TEL suggests: **Which movie genres have the highest weighted average star ratings on IMDB?** (`imdb_stars`, `imdb_genres`) (Of course, we would still need to deal with overlap in the genres.)
- *Are comedy movies associated with lower ratings than other genres?* (Should we compare comedy to non-comedy alone? Most comedies aren't just listed as comedies.)

TEL suggests: **Which movie genres have the most star ratings on IMDB?** (`imdb_ratings`, `imdb_genres`) (Of course, we would still need to deal with overlap in the genres.)
- *What is the average number of IMDB star ratings for each genre of movie?*

TEL suggests: **Which genres are associated with longer movies?** (`length`, `imdb_genres`) (Of course, we would still need to deal with overlap in the genres.)
- *Are there differences in the mean length of films across genres?* 


### A Tougher Case

- (`year`, `imdb_genres`): *Do newer movies from the 2000s tend to have more fiction than older movies?* (How do you define fiction based on the `imdb_genres` variable?)


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
