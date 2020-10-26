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

    There is only a .317688% decrease in overall passing score after the 9th grade scores were removed and the 9th grade students were removed from the THS total students.

    Before:
    ![Student_Summary_Before](https://github.com/skanab/School_District_Analysis/blob/main/Resources/student_data_before_removing_9th.PNG?raw=true)

    After:

    ![Student_Summary_After](https://github.com/skanab/School_District_Analysis/blob/main/Resources/student_data_after_count_adjust.PNG?raw=true)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type
Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
## Summary
While the provided python code was able to meet the Colorado election commission's immediate expectations for an audit of a single congressional district, I could expand it to allow the commission to audit other statewide elections. I propose the following changes.

1) Expand the data structure to include a congressional district identifier to allow for the auditing of congressional offices statewide.
2) Expand the data structures to include an office identifier to audit other state offices like the Governor, Attorney General, and Superintendent of Schools.

 Consolidating all elections audits onto a single platform would allow the election commission to save money and increase their efficiency during election cycles.
