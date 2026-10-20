# 431 Class 17: 2026-10-22

[Main Website](https://thomaselove.github.io/431-2026/) | [Calendar](https://thomaselove.github.io/431-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2026/) | [Book](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](prof-time.png)

## Today's Slides

Class | Date | HTML | Word | Quarto | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
17 | 2026-10-22 | **[Slides 17](https://thomaselove.github.io/431-slides-2026/class17.html)** | **[Word 17](https://thomaselove.github.io/431-slides-2026/class17w.docx)** | **[Code 17](https://github.com/THOMASELOVE/431-slides-2026/blob/main/class17.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Nothing is due until Monday. The next Minute Paper is after Class 18.
2. [Project A](https://thomaselove.github.io/431-projectA-2026/) is due at 9 AM on Monday 2026-10-26.
    - Make sure you submit all of the required materials by that time.
3. The [Quiz 1](https://github.com/THOMASELOVE/431-quiz-2026) answer sketch and grading rubric is posted to our Shared Drive.
    - You should have an email from me providing details on your Quiz 1 grade, as well. 
    - A student explained why some of you came up with a particular incorrect response to Question 30. The sketch reflects this, as of Monday night.
    - I will accept Quiz 1 grading revision questions through Monday 2026-10-26 at 9 AM. Just send them to 431-help at case dot edu.
4. [Lab 5](https://github.com/THOMASELOVE/431-labs-2026/tree/main/lab5) involves building a personal website.
    - Please get started as soon as you complete Project A (if not sooner). The Lab is due Wednesday 2026-11-04 at noon.
    - There is **absolutely nothing wrong** with using AI to do [Lab 5](https://github.com/THOMASELOVE/431-labs-2026/tree/main/lab5), from my perspective, **so long as** in your email to me, you tell me precisely what tools **and** what prompts you used to do all of the work.
5. By next week, you should have read Spiegelhalter Chapters 1-3, 5 and 7-11. We'll finish the book by the end of November.
6. I've added a tab called *Attendance* to our Grade Roster on the Shared Drive.
    - The class expectation is that you will [miss no more than four in-person classes during the semester](https://thomaselove.github.io/431-syllabus-2026/12_policies.html#attendance). Missing more than four classes in the situations where I take attendance doesn't lead to a direct penalty in your grade, but it enormously reduces your opportunity to earn [bonus credit](https://thomaselove.github.io/431-syllabus-2026/11_grading.html#bonus-points) for class participation.
    - If you need to miss a class session, or even two, there is no need to contact us. Just review the materials and move on, and please feel encouraged to ask for help.
    - If you must miss **more than two** classes in a row, then it is your responsibility to email Professor Love as soon as possible to let him know. An appropriate email would read “I am unable to attend class on [specific dates] and I will complete all necessary work while I am away.” No additional explanation is required.

## References related to Multiple Imputation and Today's Slides

- Sterne JAC et al [Multiple imputation for missing data in epidemiological and clinical research: potential and pitfalls](https://www.bmj.com/content/338/bmj.b2393) BMJ 2009; 338:b2393.
- [Flexible Imputation of Missing Data, 2nd edition](https://stefvanbuuren.name/fimd/) by Stef Van Buuren
- The mice (Multivariate Imputation by Chained Equations) package [reference page](https://amices.org/mice/).
    - Stef van Buuren, Karin Groothuis-Oudshoorn (2011). [mice: Multivariate Imputation by Chained Equations in R](https://www.jstatsoft.org/article/view/v045i03). Journal of Statistical Software, 45(3), 1-67. DOI 10.18637/jss.v045.i03.
- Heymans MW and Eekhout I [Applied Missing Data Analysis with SPSS and RStudio](https://bookdown.org/mwheymans/bookmi/)
- The `mipo` (Multiple Imputation pooled object) help file [can be found here](https://rdrr.io/cran/mice/man/mipo.html).
- [Getting Started with Multiple Imputation in R](https://library.virginia.edu/data/articles/getting-started-with-multiple-imputation-in-r)
- [Multiple Imputation with the mice package](https://rmisstastic.netlify.app/tutorials/erler_course_multipleimputation_2018/erler_practical_mice_2018)

## The gt package

- <https://gt.rstudio.com/> is the main source for the package

> The gt philosophy: we can construct a wide variety of useful tables with a cohesive set of table parts. These include the table header, the stub, the column labels and spanner column labels, the table body, and the table footer.

## The glue package

- <https://glue.tidyverse.org/> is the main place to go for more information

## One Last Thing

- Rows: How is Quiz 1 going (as of Class 15 mini-survey)?
- Columns: Which response includes your best guess as to your Quiz 1 points (out of 108) (estimated in Class 16 mini-survey)?
    - 76-85 points out of 108 would be a Quiz 1 score of 70% to 79%; 86-95 points out of 108 is 80% to 88%; 96-108 points is 89% to 100%

-- | 76-85 | 86-95 | 96-108 | Total
:----: | :--: | :--: | :--: | --:
Poor | 1 | 1 | -- | 2
Fair | 4 | 3 | -- | 7
Good | 5 | 10 | 2 | 17
Very Good | 1 | 7 | 1 | 9
Excellent | -- | 1 | -- | 1
Total | 11 | 22 | 3 | 36

The percentage of these 36 students who thought they were in each category was:

- 30.5% in the 70-79% range, 61% in the 80-88% range, and 8.3% in the 89-100% range.

The actual percentage of students in each category (including all 42 students, not just the 36 who answered these two mini-surveys) was:

- 24% in the 70-79% range, 21% in the 80-88% range, and 40% in the 89-100% range, with the rest below 70%.

