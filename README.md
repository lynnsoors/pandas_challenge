# pandas_challenge

District Data Analysis and Report

Background
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

Summary of Analysis
    Using pandas dataframes, data collected from 15 schools across a district was analyzed by merging all school district data. The data was summarized and sorted by school size, school type (district or charter), and school budget and per student spending. Dataframes were created to compare test scores with school size, per student spending, and school type.

District Summary
    A high-level snapshot of the district's key metrics in a DataFrame.
School Summary
    Summary of key metrics about each school.
Highest-Performing Schools (by % Overall Passing)    
    Top 5 performing schools
Lowest-Performing Schools (by % Overall Passing)
    Bottom 5 performing schools
Math Scores by Grade
    Average math scores by grade level in each school
Reading Scores by Grade
    Average reading scores by grade level in each school
Scores by School Spending
    Average scores by ranges of school spending per student
Scores by School Size
    Average scores by ranges of school spending by number of students
Scores by School Type
    Average scores by school type (district or charter)
    
Conclusions/Comparisons:
 - Overall school budget does not have a strong coorelation to overall student passing rates. The lowest performing school (Rodriguez High School) has nearly
    double the budget of the highest performing school (Cabrerea High School). Cabreara High School spends <$585 per student, while Rodriguez High School spends 
    $645-$680.
 - Schools that are small to medium size perform better than larger schools. All district schools are large, and all district schools have a lower overall passing rate
    than charter schools. This includes the 1 large charter school, Wilson High School, which has the 4th highest overall passing rate in the district.
 - Charter schools spend less money per student than district schools overall, and have higher average scores and percent passing across all categories.
    
