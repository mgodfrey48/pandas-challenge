# School Data Analysis

The code in this repository qenerates various reports using student data from a hypothetical school district. The reports include:
* District Summary - a high level snapshot (in table form) of the district's key metrics
* School Summary - an overview table that summarizes key metrics about each school
* Top Performing Schools (By % Overall Passing) - a table that highlights the top 5 performing schools based on % Overall Passing
* Bottom Performing Schools (By % Overall Passing) - a table that highlights the bottom 5 performing schools based on % Overall Passing 
* Math Scores by Grade - a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school
* Reading Scores by Grade - a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school
* Scores by School Spending - a table that breaks down school performances based on average Spending Ranges (Per Student)
* Scores by School Size - repeat of the breakdown by spending, but with schools grouped based on a reasonable approximation of school size (Small, Medium, Large)
* Scores by School Type - repeat of the breakdown by spending, but with schools grouped based on school type (Charter vs. District)

After generating each summary table, I made the following observations:
* It appears that students at schools with more than 2000 students perform worse overall in every subject analyzed than schools with less than 2000 students.
* Additionally, it appears that the schools that are spending less money per student are also the schools that have students performing better on each subject test.


## To produce the analysis on your computer:
1. Clone this repository to your computer
2. In the PyCitySchools directory, open `PyCityShools_starter.ipynb` in a jupyter notebook and run the code in each cell
