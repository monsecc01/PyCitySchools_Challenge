# PyCity Schools Challenge

## Resources
Data Source: 
[schools_complete.csv](https://github.com/monsecc01/PyCitySchools_Challenge/blob/main/schools_complete.csv) and 
[students_complete.csv](https://github.com/monsecc01/PyCitySchools_Challenge/blob/857705264cda2b7c54b06b5dfb921e4b3f60081c/students_complete.csv)

Code: [PyCitySchools_Challenge](https://github.com/monsecc01/PyCitySchools_Challenge/blob/5a8b5506e877452db4303decf69ad315eaf99d24/PyCitySchools_Challenge.ipynb)

Software: Python 3.9, Visual Studio Code 1.55.1

----
## Overview of the school district analysis:
The purpose of this analysis is to provide the school board with an evaluation of reading and math grades for schools in the school district. Due to evidence of academic dishonesty, were asked to omit Thomas High School ninth grade reading and math grades in the analysis while maintaining the rest of the data intact. We will be providing a report to describe how omitting Thomas high school data affects the overall analysis. The metrics we are asked to provide in the report are:
* School Type
*	Total Students
*	Total School Budget
*	Per Student Budget
*	Average Math Score
*	Average Reading Score
*	% Passing Math
*	% Passing Reading
*	% Overall Passing

We will also be providing the following summary tables as part of the report:
*	High and Low performing schools
*	Scores by school spending
*	Scores by school size
*	Scores by school type

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

* How is the district summary affected?
  * The district summary was not significantly affected. The main change was the number of students decreased from 39,170 to 38,709 students. The metrics for math and reading scores only changed by a fraction of a percentage. This might be because we have such a large data set and the number of replaced 9th grade scores were minimal in comparison. One metric that remained the same was the district's average reading score (81.9.)
![districtSummary_original](https://user-images.githubusercontent.com/81447450/115161222-0a997380-a062-11eb-8e00-c5c311a88a62.png)
![districtSummary_noTHS](https://user-images.githubusercontent.com/81447450/115161226-0d946400-a062-11eb-84c0-1320ab5af265.png)

* How is the school summary affected?
  * The school summery math and reading scores were not drastically changed. The removal of 9th grade data decreased Thomas High School's math and reading score averages and percentages, but only by a fraction of a percentage.
 ![THS_school_summary_noTHS](https://user-images.githubusercontent.com/81447450/115161249-45031080-a062-11eb-9dac-20a06598d642.png)

*	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	  * Removing 9th grade math and reading data does not affect Thomas High School’s performance; the school remained the second highest performing schools in the district.
 ![High_performing_schools_noTHS](https://user-images.githubusercontent.com/81447450/115161318-a2975d00-a062-11eb-8ff3-f922284f1f60.png)

How does replacing the ninth-grade scores affect the following:
*	Math and reading scores by grade.
	 * The only change to this metric is that there are NaNs in the 9th grade column for Thomas High School. 
![math_scores_by_grade_noTHS](https://user-images.githubusercontent.com/81447450/115161326-b347d300-a062-11eb-9c2f-21b1e85aa3f9.png)

*	Scores by school spending
	 * The scores by school spending metrics are not affected by the replacement of ninth-grade scores. The metrics are the same, this could be because changes to score averages are a fraction of a percentage. 
![scores_by_spending_noTHS](https://user-images.githubusercontent.com/81447450/115161380-fa35c880-a062-11eb-95ea-c049946a2e98.png)

*	Scores by school size
	 * The scores by school size metrics are not affected by the replacement of ninth-grade scores.
![scores_by_size_noTHS](https://user-images.githubusercontent.com/81447450/115161396-091c7b00-a063-11eb-824b-a9a22c74b000.png)

*	Scores by school type
	 * The scores by school type metrics are not affected by the replacement of ninth-grade scores.
![scores_by_type_noTHS](https://user-images.githubusercontent.com/81447450/115161405-120d4c80-a063-11eb-8d2a-5941d4feecac.png)
