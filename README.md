# School District Analysis

## Overview
The school board believes that the 9th-grade math and reading score from Thomas High School have been altered. To ensure that testing standards are met, they have asked that Maria remove the compromised 9th-grade data and rerun the analysis.

Analysis to include:
* How is the district summary affected?
* How is the school summary affected?
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative * to the other schools?
* How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
* Scores by school spending
* Scores by school size
* Scores by school type

## Analysis Results

* How is the district summary affected?  

    We see a small reduction in Math, Reading and Overall passing scores due the the removal of 9th grade scores.

    Before:
    ![District_Summary_Before](https://github.com/skanab/School_District_Analysis/blob/main/Resources/District_Summary_Before.PNG?raw=true)

    After:
    ![District_Summary_After](https://github.com/skanab/School_District_Analysis/blob/main/Resources/District_Summary_After.PNG?raw=true)


* How is the school summary affected?

    * 0.08648% decrease ub % math score
    * 0.29013% decrease in % reading score
    * 0.31768% decrease in % overall passing score 

    Before:
    ![Student_Summary_Before](https://github.com/skanab/School_District_Analysis/blob/main/Resources/student_data_before_removing_9th.PNG?raw=true)

    After:

    ![Student_Summary_After](https://github.com/skanab/School_District_Analysis/blob/main/Resources/student_data_after_count_adjust.PNG?raw=true)


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    It dropped the math, reading and overall percentages down by 30% until the THS student count was upgdate to remove the 9th graders.

    ![Student_Summary_After](https://github.com/skanab/School_District_Analysis/blob/main/Resources/student_data_before_count_adjust.PNG?raw=true)



* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
        * no math or reading scores can be calu
    ![Math by Grade](https://github.com/skanab/School_District_Analysis/blob/main/Resources/math_by_grade.PNG?raw=true)
    * Scores by school spending
    * Scores by school size
    * Scores by school type


## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
