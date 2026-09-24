# 431 Class 10: 2026-09-24

[Main Website](https://thomaselove.github.io/431-2026/) | [Calendar](https://thomaselove.github.io/431-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2026/) | [Book](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](https://imgs.xkcd.com/comics/assigning_numbers.png) [Source](https://xkcd.com/2610)

## Today's Slides

Class | Date | HTML | Word | Quarto | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
10 | 2026-09-24 | **[Slides 10](https://thomaselove.github.io/431-slides-2026/class10.html)** | **[Word 10](https://thomaselove.github.io/431-slides-2026/class10w.docx)** | **[Code 10](https://github.com/THOMASELOVE/431-slides-2026/blob/main/class10.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Feedback on the Minute Paper after Class 09 is now available at <https://tinyurl.com/431-2026-feedback-min-09>.
    - Scores on the Minute Paper are in the Grade Roster.
    - Those of you with a score of 9 instead of 10 should interpret that as an indication that I wasn't getting what I'm hoping for in your responses to the two main questions: (1) What is the most important thing you've learned during 431 in the past week or so? (2) What question (about 431 or R or statistics) would you most like Dr. Love to answer for you at present?
2. The Lab 3 answer sketch and grading rubric will be posted to our Shared Drive as soon as all students have submitted the Lab successfully to Canvas, or Friday at noon, whichever comes first.
3. Please install [the ggExtra package](https://github.com/daattali/ggExtra). It's posted to our [list of R packages to install](https://github.com/THOMASELOVE/431-packages).
    - If you haven't updated your R Packages in a while, it's [definitely time to do that](https://thomaselove.github.io/431-2026/software.html#updating-your-r-packages).
4. Last time, we talked about the favorite movies. Here's an update on [some of those results](https://github.com/THOMASELOVE/431-classes-2026/blob/main/movies/class09_results.md).

## About Loading R Packages

These are the things I look for in a proper R Setup in your Quarto file. This list is also now part of our general [Tips for Labs and Projects page](https://github.com/THOMASELOVE/431-labs-2026/blob/main/tips.md).

1. Your Quarto includes `#| message: false` at the start of the code chunk.
2. You include `knitr::opts_chunk$set(comment = NA)` at the start of your code.
3. If you are going to source in a script, like `Love-431.R`, you do it next.
4. You then load packages. I typically start with janitor, patchwork and naniar, assuming I am going to use them.
5. Your last two packages loaded are **easystats** then **tidyverse**.
6. You **do not** load packages that are part of easystats or part of the tidyverse separately - this is an extremely common problem for people who use AI to help them code, and makes it really easy for us to take away some points for not being tidy about what you're doing.
    - The [list of packages contained in easystats is here](https://easystats.github.io/easystats/#getting-started). It includes report, correlation, modelbased, bayestestR, effectsize, see, parameters, performance, insight and datawizard.
    - The list of [core packages loaded by tidyverse is here](https://tidyverse.org/packages/#core-tidyverse). It includes ggplot2, dplyr, tidyr, readr, purrr, tibble, stringr, forcats and lubridate.
7. You set a theme for your ggplots last, with `theme_set(theme_bw())`, or another option. Some I like include `theme_modern()`, `theme_lucid()`, `theme_light()`, as well as some of the options [described here](https://ggplot2-book.org/themes#sec-themes) and elsewhere.

- I'll be looking at your [Project A check-in](https://thomaselove.github.io/431-projectA-2026/#the-check-in) Quarto files personally, and in particular, at the packages you're loading and how you're loading them. Load all of the R packages you use, and not ones that you don't.

----------

## Reminders

1. The [Project A check-in](https://thomaselove.github.io/431-projectA-2026/#the-check-in) is due Wednesday 2026-09-30 at noon.

## Reading (before Class 11)

- Spiegelhalter *The Art of Statistics* Chapter 8 (Probability - the Language of Uncertainty and Variability)
- American Statistical Association 2016 [ASA Statement on p-values: Context, process and purpose](https://amstat.tandfonline.com/doi/full/10.1080/00031305.2016.1154108) skim the main article ([pdf](https://amstat.tandfonline.com/doi/epdf/10.1080/00031305.2016.1154108?needAccess=true): pp. 129-133), as well as four of the brief [supplements](https://doi.org/10.6084/m9.figshare.3085162.v7), specifically those written by Donald A. Berry, by George Cobb, by Andrew Gelman and by Anne Michele Millar.
- Next week (Classes 11-12) we will discuss the ASA material above, and material related to [the Course Book](https://thomaselove.github.io/431-book/): Chapters 12-13.

## One Last Thing

Check out <https://walzr.com/who-up/>

