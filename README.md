# School Data Analysis Challenge 4

## Overview of Project

Maria wanted to conduct an analysis of the school district to capture key information about the schools and its students. The purpose of this analysis is to import data from multiple CSV files and explore tools provided by Jupyter Notebook and Pandas. This school district analysis was smoothly performed by using key features built into Jupyter and Pandas to provide the following deliverables mentioned below. 

- Deliverable 1: Replacement of ninth-grade reading and math scores for Thomas High School 

- Deliverable 2: Repeat of the school district analysis
	- The district summary
	- The school summary
	- The top 5 and bottom 5 performing schools, based on the overall passing rate
	- The average math score for each grade level from each school
	- The average reading score for each grade level from each school
	- The scores by school spending per student, by school size, and by school type

- Deliverable 3: A Written Report for the School District Analysis


## School District Analysis Results

How is the district summary affected?
- The impact of negating students reading and math scores from Thomas High School for the district summary was minimal. Overall, the discrepancies ($\Delta$) from the original district summary were less 0.3 across the board for the calculated averages and percentages.


How is the school summary affected?
- The impact of negating students reading and math scores from Thomas High School for the school summary was minimal. Overall, the discrepancies ($\Delta$) from the original school summary are only observable for Thomas High School's calculated averages and percentages.

How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
- Replacing the ninth graders' math and reading scores actually didn't affect Thomas High School's performance relative to other schools. Solely considering tenth-twelfth graders, Thomas High School remained in second place for school performance. 

How does replacing the ninth-grade scores affect the following:

- Math and reading scores by grade
	- There is no change besides the ninth graders' math and reading scores from Thomas High School being negated in the new DataFrames. Everything else remained the same. 

- Scores by school spending
	- There is no noticeable change. Everything looks the same as before, but that doesn't entirely mean that there aren't any changes. The way the averages and percentages are formatted gives this illusion. Displaying another significant figure would demonstrate these changes are affecting the DataFrames values, but the overall displayed information is not being altered.

- Scores by school type
	- There is no noticeable change similar to what was observed with scores by school spending. Everything looks the same as before, but that doesn't entirely mean that there aren't any changes. The way the averages and percentages are formatted gives this illusion. Displaying another significant figure would demonstrate these changes are affecting the DataFrames values, but the overall displayed information is not being altered. 


## Summary 

1. The district summary DataFrame was slightly impacted due to the negation of ninth grade math and reading scores from Thomas High School. 
2. There were observable changes in the school summary when indexing information about Thomas High School. Mainly when retrieving information about the average math and reading scores as well as the percentage of passing students for math, reading, and for both subjects.
3. Replacing the ninth graders' math and reading scores did not affect Thomas High School's performance position relative to other schools. It remained in second place for top performing schools. 
4. Also, there were changes to the math and reading scores by grade DataFrames. Mainly presented in the Thomas High School index for ninth graders displaying NaN for both DataFrames. Lastly, when observing the Scores by school size and Scores by school type DataFrames it seemed that there were no visible changes. However, upon further inspection it was noticed that the values did change but not enough to significantly alter the DataFrames relative to the original DataFrames. 