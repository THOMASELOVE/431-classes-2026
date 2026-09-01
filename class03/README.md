# 431 Class 03: 2026-09-01

[Main Website](https://thomaselove.github.io/431-2026/) | [Calendar](https://thomaselove.github.io/431-2026/calendar.html) | [Syllabus](https://thomaselove.github.io/431-syllabus-2026/) | [Book](https://thomaselove.github.io/431-book/) | [Contact Us](https://thomaselove.github.io/431-2026/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/431-data)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | get help | lab submission | for downloads

![](https://imgs.xkcd.com/comics/iso_8601.png)  Source: <https://xkcd.com/1179/>

## Today's Slides

Class | Date | HTML | Word | Quarto | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
03 | 2026-09-01 | **[Slides 03](https://thomaselove.github.io/431-slides-2026/class03.html)** | **[Word 03](https://thomaselove.github.io/431-slides-2026/class03w.docx)** | **[Code 03](https://github.com/THOMASELOVE/431-slides-2026/blob/main/class03.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- The HTML link provides the RevealJS version of the slides that I suggest you focus on during class, as it's the [most capable format](https://quarto.org/docs/presentations/revealjs/).
- Some people prefer the Word version to the HTML version for live note-taking, so I've provided a link to download that version.
- The Quarto file link provides the code I used (in [Quarto](https://quarto.org/)) to build the slides. Hit the download button after clicking the link above if you want the `.qmd` file.
- To print the HTML slides **to pdf**, [follow these instructions](https://quarto.org/docs/presentations/revealjs/presenting.html#print-to-pdf) using Google Chrome as your browser.
- We (attempt to) record all 431 classes via Zoom and post the recording to Canvas.

## Announcements

1. **Email Test**: On Sunday 2026-08-30, I sent an email entitled **431 Student Email List Test for 2026**. If you gave me a second email, check there, as well as your CWRU account, please.
    - If you did not receive this email where you wanted to get it, please **speak with me or email me** before you leave the room today to let me know that. 
2. Please feel encouraged to email `431-help` at `case` dot `edu` at any time. We know how to turn off email alerts when we're not available, and we'll respond when we can.
3. I republished the [Course Book](https://thomaselove.github.io/431-book/) on 2026-08-30 to fix a typo in the definition of the [median absolute deviation](https://thomaselove.github.io/431-book/formulas.html#the-median-absolute-deviation) in Appendix E.
4. **Read the Syllabus**: I know that 31 of this year's 45 students have read [the syllabus](https://thomaselove.github.io/431-syllabus-2026/) carefully.
5. In the Welcome to 431 survey, I asked "What has made your **favorite university classes** your favorite?" [Behold](favorite_classes.md) an AI-generated summary of those responses, if you're interested.
6. **Class 2 Slides**: In class 02, I only discussed Slides 1-37. The important parts of the rest of those slides (old Slides 38-79) will appear today (and as needed) later this term.
7. An HTML file of the `class03_toothgrowth_complete` result I will discuss today in class [is available for download here](class03_toothgrowth_complete.html).
    - Click on the download arrow, save to your desktop, *then* open in your favorite browser.
    - All of the other files for today are found on our [431 Data page](https://github.com/THOMASELOVE/431-data).
8. The 431 [Project A instructions](https://thomaselove.github.io/431-projectA-2026/) are worth reading. We'll discuss them a bit after our break.

## There is a Minute Paper due TOMORROW (Wednesday 2026-09-02) at noon.

The link is <https://tinyurl.com/431-2026-minute-03>. 

- You will need to be logged into Google **via your CWRU account** to access each Minute Paper form.
- Every Minute Paper asks a few questions, and should take less than 5 minutes to answer.
    - I always ask some form of "What was the most important thing you learned (in 431) recently?" and "What question (about 431 or R or statistics) would you most like Dr. Love to answer for you at present?". There's also always an opportunity for you to leave a comment or additional questions.
    - Some Minute Papers (like this one) will ask you about your attendance in the most recent class.
    - Each of them also asks some other things.
    - I write a feedback document Wednesday after the deadline and we will discuss that in class Thursday.
- Respond to each Minute Paper regardless of whether you attended the last class. The Minute Papers are a [part of your grade](https://thomaselove.github.io/431-syllabus-2026/11_grading.html#building-a-course-grade).
- For more on the Minute Papers, [visit their page here](https://github.com/THOMASELOVE/431-minute-2026).

-------------

## Reminders

1. Don't forget to complete the [Minute Paper after Class 3](https://tinyurl.com/431-2026-minute-03) by noon Wednesday 2026-09-02.
2. [Lab 1](https://github.com/THOMASELOVE/431-labs-2026/tree/main/lab1) is due next Wednesday 2026-09-09 at noon.
3. If you did not receive the 431 Student Email List Test for 2026 where you wanted to get it, **speak with me or email me** now.
4. Details still not resolved as of 1:30 PM Monday:
    - **Kimberly Lin** and **Luka Mitar** need to resolve their enrollment (and record the pronunciation of their full names to SIS, too.)
    - **Enysah Roberts** needs to re-record her first and last name at SIS.

## One Last Thing

Here are nine of the interesting facts about students in this class, plus a fact about me. Do you recognize yourself here?

1. I am an international student from Mongolia.
2. I am a dog mom and have Type 1 diabetes, and I used to be a pre-school teacher.
3. I compose music in my free time.
4. I worked as a produce/floral clerk in a retail grocery.
5. I was a state finalist in the Geography Bee, back in middle school.
6. I got my private pilot license at age 16, before I got my drivers license.
7. I am fluent in three languages and can understand and speak two more pretty well.
8. I recently became an aunt! I really want to meet my nephew in person, when I can get to Korea.
9. I have visited around 25 of the 63 US National Parks.
10. Dr. Love won trophies for singles and doubles play in badminton for [his high school](https://bhs.southcountry.org/families/wall-of-fame). His father was once a Long Island age group champion in the game.

## The Fantasticks 

I am appearing in the musical [The Fantasticks](https://theatreinthecircle.org/) at Theatre in the Circle (located at Judson Manor, steps from the CWRU campus) on September 11-12. For more information or to purchase tickets, visit https://theatreinthecircle.org/. The Sunday September 13 performance is already **sold out**. Please feel no obligation whatsoever to attend.
