# School_District_Analysis
## Overview 
The purpose of this analysis was to analyze proficiency testing and financial data for 15 schools in a school district. Suspicions of academic dishonesty spurred the analyst to replace 9th grade proficiency testing scores at Thomas High School with a value of NaN and to reconduct the analysis with the new student data.
## Results
### How is the district summary affected?
The original district data included 39,170 students from 15 schools within a district. Because of suspicions of academic dishonesty, all 9th grade math and reading scores from Thomas High School were replaced with a NaN value, reducing the number of students in the data set to 38,709. 
Disrict summary df: https://github.com/ChrisBarton107/School_District_Analysis/blob/main/Resources/District_Summary.png
### How is the school summary affected?
The school summary data was altered considerably in regards to Thomas High School data. This new data included:
- Student count included Thomas High School 10-12 graders
- Average Math score: Increased from 83.35% to 83.85%
- Average Reading score: Increased from 83.39% to 83.89%
- % Passing Math: Increased from  66.91% to 93.18%
- % Passing Reading: Increased from 69.66% to 97.01%
- % Overall Passing: Increased from 65.07% to 90.60%<br>
School summary df: https://github.com/ChrisBarton107/School_District_Analysis/blob/main/Resources/Per_School_Summary_2.png
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing 9th grade math and reading proficiency scores improved Thomas High School's performance relative to other schools and saw their standing elevate to second overall amongst charter schools and second overall among the 15 schools in the district. 
### How does replacing the ninth-grade scores affect the following:
Applying the NaN value to all math and reading proficiency scores for 9th graders at Thomas High School impacted the analysis in the following ways
- Math and reading scores by grade
  - Math and reading scores for 9th graders at Thomas High School were replaced with the value of NaN while scores for 10th-12th graders at Thomas High School remained the same. Other schools in the district analysis were not greatly impacted by the new data.
- Scores by school spending
  - Schools in the analysis with less funding received higher overall passing test scores than schools with more funding.
- Scores by school size
  - Scores in the small and large categories remained the same while schools in the medium category increased approximately 5%.
- Scores by school type
  - Percentage of overall passing increased for charter schools
### Summary
