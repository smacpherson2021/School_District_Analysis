# School_District_Analysis

## Overview of the school district analysis: 
The school board has notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. This analysis will replace the math and reading scores for Thomas High Schill with NaNs while keeping the rest of the data intact. With these scores replaced the school district analysis will be performed again and this report will describe how these changes affected the overall analysis. 

## Results:
- ### How is the district summary affected?

Removing the grade 9 scores for THS has the effect of slightly reducing all the score and % numbers overall.<br /><br />
After Adjustment:<br />
![1_District_Summary_Adjusted.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/1_District_Summary_Adjusted.PNG)
Before Adjustment:<br />
![1_District_Summary_Original.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/1_District_Summary_Original.PNG)
 
- ### How is the school summary affected?

Only the results for the Thomas High School were slightly reduced for Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, $ Overall Passing<br /><br />
After Adjustment:<br />
![2_Per_School_Summary_REPLACED.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/2_Per_School_Summary_REPLACED.PNG)
Before Adjustment:<br />
![2_Per_School_Summary_Original.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/2_Per_School_Summary_Original.PNG)

- ### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Performance Rankings for both Top and Bottom schools are unaffected by replacing the 9th graders' math and reading scores<br /><br />
Top Schools After Adjustment:<br />
![4_Top_Schools_Adjusted.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/4_Top_Schools_Adjusted.PNG)
Top Schools Before Adjustment:<br />
![4_Top_Schools_Original.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/4_Top_Schools_Original.PNG)

<br />

Bottom Schools After Adjustment:<br />
![5_Bottom_Shoolds_Adjusted.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/5_Bottom_Shoolds_Adjusted.PNG)
Bottom Schools Before Adjustment:<br />
![5_Bottom_Shoolds_Original.PNG](https://github.com/smacpherson2021/School_District_Analysis/blob/main/Resources/pics/5_Bottom_Shoolds_Original.PNG)


- ### How does replacing the ninth-grade scores affect the following:

  - #### Math and reading scores by grade
  
  Not sure, could say that 9th grade scores for THS for both reading and math were replaces by NaN and not including in the schools overall calculation to ensure if any scores were tampered with they would be excluded

  - #### Scores by school spending
  
  Has no affect on the results
  ![8_Scores_By_School_Spending_Adjusted.PNG](TargetUrl)
  ![8_Scores_By_School_Spending_Original.PNG](TargetUrl)

  - #### Scores by school size

  Has no affect on the results
  ![9_Scores_By_School_Size_Adjusted.PNG](TargetUrl)
  ![9_Scores_By_School_Size_Original.PNG](TargetUrl)

  - #### Scores by school type

  Has no affect on the results
  ![10_Scores_By_School_Type_Adjusted.PNG](TargetUrl)
  ![10_Scores_By_School_Type_Original.PNG](TargetUrl)


## Summary:

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

After reading and math scores for the ninth grade at Thomas High School were replaced with NaNs

The district summary changed as follows:
Field   Original  Adjusted
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
$ Overall Passing

The School Summary changed only for Thomas High School as follows:
Field   Original  Adjusted
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
$ Overall Passing


