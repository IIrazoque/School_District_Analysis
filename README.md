# School_District_Analysis
School District Analysis using python and jupyter notebook  
## Project Overview 
The purpose of this analysis was to gather details on school district performance based on Math and Reading scores. During the evaluation analysis it was discovered 9th grade scores (both math & reading) were altered. During the dishonest investigation we are to re-calculate math and reading percentages affecting school summaries.
Using the loc() method we were able to re-factor the code to replace 9th grade scores (math & reading) with NaN. The student data frame shows a total of 641 were replaced with NaN values 
![This is an image](https://github.com/IIrazoque/School_District_Analysis/blob/85b0586db81392b829e442ceced78e2579288368/Resources/NaN_values_641.PNG)
## Results 
Since we are to remove 9th grade math & reading score, the District Summary Data Frame created is affected by how we calculate averages and passing math and reading percentages. 
### Before – District_Summary_DF (with Thomas High School 9th graders)
![This is an image](https://github.com/IIrazoque/School_District_Analysis/blob/85b0586db81392b829e442ceced78e2579288368/Resources/district_summary_df_before.PNG)

### After – District_Summary_DF (without Thomas High School 9th graders)
![This is an image](https://github.com/IIrazoque/School_District_Analysis/blob/85b0586db81392b829e442ceced78e2579288368/Resources/district_summary_df_after.PNG)
We are now calculating math & reading averages using the new student count of 38,709 (excluding 9th graders from Thomas High School of 641 students. Slight changes were seen in “Average Math Score, % Passing Math Scores,  % Passing Reading Scores and % Overall Passing. 
The School Summary is also affected, and new math & reading percentages need to be calculated. In the new per_school_summary_df we can see Math and Reading percentages  drastically drop since we left the old total student count (this count includes the 9th graders from Thomas HS).
School Summary Data Frame with Old Total Student Count – affecting math and reading percentages
![This is an image](https://github.com/IIrazoque/School_District_Analysis/blob/066da0f844df3d8b57455c27a8a0b1c2922178a7/Resources/THS_per_school_summary%20without%209%20graders.PNG)
School Summary Data Frame with Old Total Student Count – updated  new student count. This count exclude 9th graders from Thomas HS 
![This is an image](https://github.com/IIrazoque/School_District_Analysis/blob/85b0586db81392b829e442ceced78e2579288368/Resources/per_school_summary_top5after.PNG)
## Summary 
Math and reading scores remain slightly unchanged for the following – 
### Scores by school
Before 
![this is an image](https://github.com/IIrazoque/School_District_Analysis/blob/066da0f844df3d8b57455c27a8a0b1c2922178a7/Resources/scores%20by%20school%20before_math_after.PNG)

After analysis 
![this is an image](https://github.com/IIrazoque/School_District_Analysis/blob/066da0f844df3d8b57455c27a8a0b1c2922178a7/Resources/scores%20by%20school%20before_math.PNG)

### Scores by school spending and school Size

Before
![this is an image](https://github.com/IIrazoque/School_District_Analysis/blob/066da0f844df3d8b57455c27a8a0b1c2922178a7/Resources/scores%20by%20schol%20spending%20before.PNG)

After analysis
![this is an image](https://github.com/IIrazoque/School_District_Analysis/blob/066da0f844df3d8b57455c27a8a0b1c2922178a7/Resources/scores%20by%20school%20spending%20after.PNG)
