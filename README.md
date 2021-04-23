# Pandas challenge: PyCitySchools
 
In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

This challenge gives practice with excercises that process data for 39,169 students across 14 schools.

# Tasks:
## District Summary

Create a high level snapshot  of the district's key metrics.
- Total Schools
- Total Students
- Total Budget
- Average Math Score
- Average Reading Score
- % Passing Math (The percentage of students that passed math.)
- % Passing Reading (The percentage of students that passed reading.)
- % Overall Passing (The percentage of students that passed math and reading.)

![District summary](https://github.com/Jeffsfine/pandas-challenge/blob/main/Images/District%20summary.png)

## School Summary

Create an overview table that summarizes key metrics about each school, including:

- School Name
- School Type
- Total Students
- Total School Budget
- Per Student Budget
- Average Math Score
- Average Reading Score
- % Passing Math (The percentage of students that passed math.)
- % Passing Reading (The percentage of students that passed reading.)
- % Overall Passing (The percentage of students that passed math and reading.)

![School Sumamry](https://github.com/Jeffsfine/pandas-challenge/blob/main/Images/School%20summary.png)

## Scores by School Spending

Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:

- Average Math Score
- Average Reading Score
- % Passing Math (The percentage of students that passed math.)
- % Passing Reading (The percentage of students that passed reading.)
- % Overall Passing (The percentage of students that passed math and reading.)

![Scores by school spending](https://github.com/Jeffsfine/pandas-challenge/blob/main/Images/Scores%20by%20School%20Spending.png)

Other reports: 

- Top Performing Schools (By % Overall Passing)
- Bottom Performing Schools (By % Overall Passing)
- Math Scores by Grade
- Reading Scores by Grade
- Scores by School Size
- Scores by School Size

## Notable Trends

* Out of 39,170 students, average reading score for the set is 81.87. This score is higher than the average math score, 78.98.
<br> The passing rate of reading 85.80%. This rate is higher than the math passing rate, 74.98 %.
<br>  The overall passing rate is 65.17%. Students in this data set score higher in reading than math.

* 7 schools in the set are district schools. 8 schools are charter Schools. The number of students in any one school ranged between 427 students (Holden High School) to 4976 students (Bailey High School). 
<br> The school summary found that district schools have more students than charter schools.

* The school with the largest budget is Bailey High School, at $3,124,928.00. The lowest budget school is Holden High School at $248,087.00.
<br> While it's budget is the highest of all schools, Bailey High School is not in the list of top performing schools. 
<br> This would be an important finding to bring up to Bailey High School and the Overseer of these schools in order to better allocate the resources to help the students of the school. 

* Huang High School has the highest budget per student at $655.00. 
<br> Wilson High School has the lowest budget per student at $578.00. 
<br> Huang High School is one of the bottom performing schools while having the highest budget per student. 
<br> This finding should be brought up to Huang High School and the Overseer of the schools in the the same way Bailey High School's high budget issue.

* The district schools budget ($17,347,923.00) is higher than that of the charter schools budget ($7,301,505.00), 
<br> although the budget per student of charter schools ($4,796.00) is greater than that of district schools ($4,505.00).  

* In average score, percent passing, and overall score,Charter schools have a greater scores than District schools. 

* Grade 11 students at Holden High School holds a higher average Math score (85) comparing all schools and grades. 
<br> Holden High School grade 12 students possess a higher average reading score (84.670).

Two important findings within this dataset.
<br>
<br>
Budget per student correlates positively with:
* Average math score
<br>
<br>
But correlates negatively with:
* Pverage reading score
* Percent of passing math 
* Percent of passing reading 
* Overall passing

*
