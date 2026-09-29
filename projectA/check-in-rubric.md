## Grading Rubric for Project A Check-in

The [Project A Check-in form](https://tinyurl.com/431-2026-projectA-checkin) is due Wednesday 2026-09-30 at noon.

Here's how Dr. Love plans to review your form (the TAs will not be involved in this initial review):

Each of these is a Yes or No question.

1. Did you complete the form on time, including submitting your Quarto file?
2. If you're working with a partner, did you each complete the form on time, with the same responses and Quarto file?
    - If you're not working with a partner, then question 2 is an automatic YES.
3. Given your stated random seed, do I get the same two states you did?
4. Given your two selected states, do I get the same number of rows (counties) you did?
5. Do you have the correct number of columns in your `projA_master` tibble?
6. Is the minimum value of the percentage of adults reporting poor or fair health from your tibble appropriate?
7. Is the number of counties with the value of Yes for `water_v` from your tibble appropriate?
8. Is the minimum value of the `lbw_old` variable from your tibble appropriate?
9. Are the YAML and R Setup section of your Quarto file appropriate?
10. When Dr. Love runs your Quarto file, does the resulting HTML look appropriate, with no meaningful problems?
    - The template includes 17 sections. The ones we will look at in reviewing the Check-In Quarto file are the first seven, which should be labeled:
        - R Packages, Data Ingest, Selecting States, Create the Master Tibble, Manage Names and Types, Create a New Factor and Printing the Tibble
    - You should have completed all of the tasks involved in [Getting the Data](https://thomaselove.github.io/431-projectA-2026/#getting-the-data) and completed all tasks (A-J) for [Managing the Data](https://thomaselove.github.io/431-projectA-2026/#managing-the-data), which actually takes you through Section 9 of the Project A Template, but we will focus our review on the first seven.
    - Your `projA_master` tibble should contain missing values. You should NOT remove those values as part of the work you do for the check-in. Dealing with missing values happens in Sections 10-13 of the Quarto template, where you're making comparisons and analyzing the data.

**You will receive the grade of 20 on the Project A check-in if you have a YES for Questions 1-10.**




