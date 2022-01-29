# School District Analysis

### Overview of the school district analysis:

In this analysis, I assisted the school board to analyze results based on various key metrics to identify how each school has performed in Math, and Readings. Also, there were other detaild analysis of spend, budget per school, and how that may have impacted students, students' results. Unfortunately, there was evidence of academic dishonesty; reading and math grades for Thomas High School (THS). Specifically, THS ninth graders appear to have been altered. Although the school board unaware of the full degree of academic dishonesty, they want to uphold state-testing standards. As a result, I needed to use methods which will assist in obtaining results per state-testing standard yet provide the analysis for the rest of the schools in the board in many required metrics. In my analysis, I have replaced the math and reading scores for Thomas High School with NaNs(not available) while keeping the rest of the data intact to get the desired output.

### Resources:
Python, Jupyter Notebook, school and student data supplied in CSV format

### Results:
Since I needed to substitute all Thomas High School (THS) 9th grade results with NaNs, this replacements in Math and Reading scores slightly impacted the overall results in the district. All average scores and passing percentages, in district level, dropped slightly.
Previously, before substituting the 9th grade Math and Reading scores, THS average were 66.91% and 69.66% respectively. Correcting the average for Math and Reading scores to 93.18% and 97.13% changes the overall passing percent to 90.63%. While THS 9th graders exclusion made significant change by school level Math, Reading and Overall percentage, in the aggregate level the impacts were not noticeable for Scores by school spending, Scores by school size or Scores by school type. Afterall, total THS 9th graders were only 1.18% of all the students in the district. A summary of the impact is below for all 7 metrics:

•	District summary: very little change, almost similar.
![District Summary](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/District%20Summary.png)

•	School summary: All school remains same, except THS. Math & Readings percentage have gone up significantly, so is the overall percentage.
![School Summary](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/School%20Summary%20THS.png)

•	Thomas High School’s (THS) performance relative to the other schools: THS is now one of the top 5 schools. Before THS was in the bottom 5 pool. A well-deserved jump followed by a solid performance
![THS Rank](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/THS%20Ranking.png)

•	Math and reading scores by grade: Remain unchanged for all school including THS, except grade 9 column shown with “nan”

•	Scores by school spending: Remain unchanged.
![Spending by Schools](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/Spend%20Summary%20by%20Scores.png)


•	Scores by school size: Remain unchanged.
![Scores by School Size](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/School%20Size%20by%20Score.png)


•	Scores by school type: Remain unchanged.

![Scores by Shcool Type](https://github.com/shamayun/School_District_Analysis/blob/main/Resources/School%20Type%20by%20Scores.png)


### Summary:
Changes to THS 9th grade only impacted 4 of the metrics. In the school summary, THS reading Passing in Math, Reading and overall passing was changed significantly. Resulted a sharp change in school performance, from bottom 5 to 2nd ranked shcools. Also, there were no information was available in grade level summary, showing only NaN. All other metrics remained unchanged.

