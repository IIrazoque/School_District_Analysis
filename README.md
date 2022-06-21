# School_District_Analysis
School District Analysis using python and jupyter notebook  
## Project Overview 
The purpose of this analysis was to gather details on school district performance based on Math and Reading scores. During the evaluation analysis it was discovered 9th grade scores (both math & reading) were altered. During the dishonest investigation we are to re-calculate math and reading percentages affecting school summaries.
Using the loc() method we were able to re-factor the code to replace 9th grade scores (math & reading) with NaN. The student data frame shows a total of 641 were replaced with NaN values 
![This is an image]
## Results 
Since we are to remove 9th grade math & reading score, the District Summary Data Frame created is affected by how we calculate averages and passing math and reading percentages. 
### Before – District_Summary_DF (with Thomas High School 9th graders)
![This is an image]

### After – District_Summary_DF (without Thomas High School 9th graders)
![This is an image]
We are now calculating math & reading averages using the new student count of 38,709 (excluding 9th graders from Thomas High School of 641 students. Slight changes were seen in “Average Math Score, % Passing Math Scores,  % Passing Reading Scores and % Overall Passing. 
The School Summary is also affected, and new math & reading percentages need to be calculated. In the new per_school_summary_df we can see Math and Reading percentages  drastically drop since we left the old total student count (this count includes the 9th graders from Thomas HS).
School Summary Data Frame with Old Total Student Count – affecting math and reading percentages
![This is an image] THS per summary without 9  
School Summary Data Frame with Old Total Student Count – updated  new student count. This count exclude 9th graders from Thomas HS 
![This is an image] per_school_summary_top5after
## Summary 
Math and reading scores remain slightly unchanged for the following – 
### Scores by school
![this is an image] Before 
“scores by school before”
![this is an image] After  
“scores by school after”
### Scores by school spending and school Size
![this is an image] Before 
![this is an image] After  
