# PyCity Schools Challenge

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
  * The district summary was not significantly affected. The metrics for math and reading scores only changed by a fraction of a percentage. The Average reading score stayed the same at 81.9%.
* How is the school summary affected?
  * Thomas High School metrics for math and reading scores were not drastically changed. The removal of 9th grade data decreased the math and reading score average and percentages, but only by a fraction of a percentage.
*	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	  * Removing 9th grade math and reading data does not affect Thomas High School’s performance; the school remained the second highest performing schools in the district.
 
How does replacing the ninth-grade scores affect the following:
*	Math and reading scores by grade.
	 * The only change to this metric is that there are NaNs in the 9th grade column for Thomas High School. 
*	Scores by school spending
	 * The scores by school spending metrics are not affected by the replacement of ninth-grade scores. The metrics are the same, this could be because changes to score averages are a fraction of a percentage. 
*	Scores by school size
	 * The scores by school size metrics are not affected by the replacement of ninth-grade scores.
*	Scores by school type
	 * The scores by school type metrics are not affected by the replacement of ninth-grade scores.
