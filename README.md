# School_District_Analysis

## Overview of the school district analysis: 
Since the school board found evidence of academic dishonesty, Maria requested a new School District Analysis in which the grades from the ninth graders from Thomas High School must be replace with NaNs. Then the new Analysis should be compared with the previous one to understand how removing the ninth graders grades affect the final School District Analysis. 

## Results: 
### How is the district summary affected?
The district summary gets affected in the total students count and in all the grade averages, see images below:

*School Summary with the complete data*
 ![distric_summary_1](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/district_summary_analysis1.PNG)

*School Summary without the ninth graders from Thomas High School*
 ![distric_summary_2](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/district_summary_analysis2.PNG)
A total of 461 students are not counted in this data.

### How is the school summary affected?
The school summary is affected in the percentage of passing math, reading, and overall passing since these percentages are calculated with the new total student count from Thomas High School. See images below:
_The averages in this image are calculated based on the total high school population of students from Thomas High School:_
 ![school_summary_1](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/school_summary_analysis1.PNG)

_The averages in the image below are calculated based on the 10th to 12th graders scores and the total amount of these students. In the table below the total students is still 1635, but the total students from 10th to 12th grades are 1174._ 
![school_summary_2](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/school_summary_analysis2.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the grades of the ninth grades does not affect the performance of Thomas High School significantly. There is a little decrease in the overall performances, but the school is still in second place on the top 5.
_Top five schools (including all the students):_
![top_five_1](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/top_school_1.PNG)
 
_Top five schools without ninth graders from Thomas High School:_
 ![top_five_2](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/top_school_2.PNG)
 
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
By removing the scores of the ninth graders from Thomas High School no grades from those students is taking into consideration. The tables below show “nan” as a result of that:

*Math Scores*

![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/math_scores_2.PNG)

*Reading Scores*

![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/redaing_scores_2.PNG)

#### Scores by school spending
Both results are identical, since the student count was not affected in the school summary Thomas High School is still in the $630-644 budget group.

*Scores by school spending with all the students:*
![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/spending_by_student1.PNG)

_Scores by school spending without the ninth graders from Thomas High School:_
![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/spending_by_student1.PNG)

#### Scores by school size
Similar case from above, the school size did not change when the grades where removed, so the score by school size chart looks identical in both analysis:
![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/score_by_size_2.)

#### Scores by school type
No significant changes were observed on these table. They are identical:
_Scores by school type with all the students:_
![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/score_by_type_1.PNG)

_Scores by school type without the ninth graders from Thomas High School:_
![](https://github.com/KatiuscaQ/School_District_Analysis/blob/main/Resources/score_by_type_2.PNG) 

## Summary: 

After reading and math scores from the ninth graders from Thomas High School were replaced with NaNs in the school summary, the following changes were observed:
1. There is no reading score for ninth graders in Thomas High School.
2. There is no math score for ninth graders in Thomas High School.
3. There is no overall passing scores for ninth graders in Thomas High School. 
4. The percentage of passing scores for Thomas High School is considering all grades except the ninth.

If all the students from the ninth grade from Thomas High School were removed from the data the school size would have change, and the budged would have not match the actual school needs. 
