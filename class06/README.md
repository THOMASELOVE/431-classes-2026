# 431 Class 06: 2026-09-10

[Main Website](https://thomaselove.github.io/431-2026/) | [Calendar](https://thomaselove.github.io/431-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2026/) | [Book](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

## Today's Slides

Class | Date | HTML | Word | Quarto | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
06 | 2026-09-10 | **[Slides 06](https://thomaselove.github.io/431-slides-2026/class06.html)** | **[Word 06](https://thomaselove.github.io/431-slides-2026/class06w.docx)** | **[Code 06](https://github.com/THOMASELOVE/431-slides-2026/blob/main/class06.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Feedback on the Minute Paper after Class 05 [is now available](https://tinyurl.com/431-2026-feedback-min-05).
2. [Lab 2](https://github.com/THOMASELOVE/431-labs-2026/tree/main/lab2) is due next Wednesday 2026-09-16 at noon.

## On Lab 1

1. The Lab 1 answer sketch is **now available** on our Shared Google Drive in the **431 Answer Sketches for Labs** folder. To view the HTML, **download** it onto your machine, then open it with your favorite browser.
2. You'll receive detailed and individual Lab 1 feedback next Tuesday 2026-09-15 before class on the Shared Drive Grade Roster.

Here are some issues people had with the mechanics (initial checks) of the Lab that we want to call to your attention:

- **Computers want to do EXACTLY what you ask them to do**, so details matter.
- **Changing the YAML Code**: Working from the top of the Quarto template, we wanted you to change the title to 431 Lab 1, and the author to your name (don't put your name in parentheses.) Your only other thing to consider changing is the theme at the bottom, where, instead of `materia` you might pick [any of these HTML themes](https://quarto.org/docs/output-formats/html-themes.html) that Quarto supports. It should look something like this, when you're finished.

```
---
title: "431 Lab 1"
author: "Elizabeth Lemon"
date: last-modified
format: 
  html:
    toc: true
    number-sections: true
    code-fold: show
    code-tools: true
    code-overflow: wrap
    embed-resources: true
    date-format: iso
    theme: materia  ## change the theme if you prefer
---
```

- **Deleting my instructions** Many of my instructions fall in callout blocks. It's important when removing those to remove both the start and end of such a box. So, for instance, just before the R Setup, I have the following, in the Lab 1 template. It's important to delete the `:::` at the end of that callout, and not just the text.

```
:::{.callout-important}

Delete **all of the instructions** we provide to you in this template,
in favor of your own words, before submitting your work. You are welcome
to retain any or all of the R code we provide in this template as part
of your response.

:::
```

- **R Setup** The last two packages you load should be (in this order) easystats and then tidyverse. Load the tidyverse last.
- **Headings and Subheadings** The template has a number of headings and subheadings included. The R Setup is designed to be unnumbered (see below) and a second-level header, while Task 1 is meant to be numbered, and a top-level header. If I wanted to split Task 1 into separate pieces with subheaders, I would use ## or even ### to get headings like 1.1 to show up in the Table of Contents automatically with that information. Note that `# Task 1` works fine, but, for instance, `#Task 1` does not. The computer needs the space after the header in order to interpret it properly.

```
## R Setup {.unnumbered}

Content

# Task 1

Content that will appear under heading 1 Task 1 in our Table of Contents 

## Interpreting my Task 1 model

Content goes here (and this will appear under heading 1.1 Interpreting my Task 1 model in the Table of Contents)
```  
- **Blank lines after every code chunk, header, and paragraph** As I have done in all of the course materials, include a blank line after every code chunk, every header and every paragraph. That way, R will format things properly.
- **Making your code more legible** To ease reading for us, please hit ENTER at least after every `|>` in R code, and after every `+` in ggplot() code. Compare:

```
task4dat <- cms_patient_experience |>
  filter(measure_cd == "CAHPS_GRP_2" | measure_cd == "CAHPS_GRP_8") |>
  pivot_wider(names_from = c(measure_cd, measure_title),
              values_from = prf_rate) |>
  rename("Communicate" = "CAHPS_GRP_2_CAHPS for MIPS SSM: How Well Providers Communicate",
         "Staff" = "CAHPS_GRP_8_CAHPS for MIPS SSM: Courteous and Helpful Office Staff") |>
  drop_na()
```

to 

```
task4dat <- cms_patient_experience |> filter(measure_cd == "CAHPS_GRP_2" | measure_cd == "CAHPS_GRP_8") |> pivot_wider
(names_from = c(measure_cd, measure_title), values_from = prf_rate) |> rename("Communicate" = "CAHPS_GRP_2_CAHPS for
MIPS SSM: How Well Providers Communicate", "Staff" = "CAHPS_GRP_8_CAHPS for MIPS SSM: Courteous and Helpful Office
Staff") |> drop_na()
```

While both will work in R, the first version is much more legible to a human.

- **Video** The video was meant to be no more than 30 seconds long. If you're well over that, editing it or reshooting it would have been the move. Make sure that the viewer can both see and hear you before you submit the work.
- **AI Usage** If you use AI, tell us what AI tools you used (Claude, Copilot, Gemini, ChatGPT) **and** how you used it. If you didn't use AI (essentially) then write the sentence we wrote in the instructions.
- **Upgrading** Upgrade R to version 4.6.1 if at all possible before completing Lab 2.
    - Also, if you're using an operating system that is elderly (like Windows 10 or macOS prior to Tahoe 26), consider upgrading your machine if possible.
- **Typos** Use spell check in RStudio to get rid of egregious typing errors (just hit F7 or click on the spelling icon)
- **Final Checks** Check your HTML before you submit it to ensure that:
    - Your title, author and date fields look OK, and
    - the Table of Contents functions properly, in particular:
        - you have a numbered section heading that is appropriate for each Task
        - when you click on a heading, the HTML file you are submitting scrolls down to that location 
- **Troubleshooting** If your Quarto file renders but has problems (like the table of contents not working), save your work, close RStudio, then re-open RStudio and select Packages ... Update and update your R packages. Then select your Project again and try rendering it again.
- Many of these tips for Labs also appear in [these tips for lab and project work](https://github.com/THOMASELOVE/431-labs-2026/blob/main/tips.md) and are linked in every Lab's instructions.

## Reading (before Class 07)

- Spiegelhalter *The Art of Statistics* Chapter 5 (Modelling Relationships using Regression)
- [R for Data Science](https://r4ds.hadley.nz/) (2nd edition): Sections 9-11 ("Visualize")
- Next week (Classes 07-08) we will discuss material related to [the Course Book](https://thomaselove.github.io/431-book/): Chapters 8-9.

## One Last Thing

Here are nine more interesting facts about students in this class, plus another fact about me. Do you recognize yourself here?

1. I am a dog mom and a certified yoga instructor, although I haven't practiced yoga in some time.
2. I enjoy playing the guitar and come from Toronto, Canada.
3. I went to Japan last year.
4. I've hiked sections of the Appalachian Trail in multiple states and I aspire to hike the entire trail.
5. I like traveling and try to get to at least one new place every year.
6. I attend the Lollapalooza music festival every year - it's my favorite weekend of the year.
7. I've worked at Cleveland's NPR station and the International Fund for Public Interest Media in Paris.
8. I have lived in Honduras and in Trinidad & Tobago.
9. I am a dancer, and I like to dance when I am working.
10. Dr. Love has performed in the musical *Sweeney Todd* (his all time favorite musical) three times, playing the Beadle, Judge Turpin, and the title role in separate Northeast Ohio productions.

## The Fantasticks

If you want to see a rehearsal video of me looking silly, visit <https://www.youtube.com/shorts/W2FGydkArEU>.
