# School_District_Analysis
## Overview
### This analysis was conducted to review the extensive Standardized Testing Performance Data of a City School Disctrict in order to help support and drive decision making as it pertains to school funding. Upon close inspection of the data, there were apparent irregularities in the collected math and reading scores of ninth graders at Thomas High School, a potential indicator of academic dishonesty. This discovery resulted in additional data clean up in order to isolate and remove the irregulraties from the dataset, preventing any impacts or distoritions of the overall findings for the remaining schools and students in the school district. A review of the comparison findings are captured in this report. 


## Findings 
***How is the district summary affected?***

**Initial Disctrict Summary**

![Initial Disctrict Summary](https://github.com/LinzStearns/School_District_Analysis/blob/main/district_summary_dishonest.png)

**Updated District Summary**

![New District Summary](https://github.com/LinzStearns/School_District_Analysis/blob/main/district_summary_minusninthgraders.jpg)

When comparing the two curated tables for the District Summary, the data shows that the Overall Passing Percentage takes a slight drop from 65.2% to 64.9%.


***How is the school summary affected?***

**Initial School Summary**
![Initial School Summary](https://github.com/LinzStearns/School_District_Analysis/blob/main/initial_school_summary.png)

Pictured above is the representation of the Initial School Summary that was conducted which reflects an Overall Passing Percentage of 91% for Thomas High School. The data is clearly showing a steep decline in Overall Passing Percentage when the ninth grade data with academic dishonesty is removed.

***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?***

When replacing the ninth graders’ math and reading scores, Thomas High School's performance relative to other schools remained relatively the same as they were ranked number two in both scenarios.


***How does replacing the ninth-grade scores affect the following:***

*Math and reading scores by grade: had the most notable impact as ninth grader data is now completely omitted from the analysis. 


*Scores by school spending:
**Initial Scores by School Spending**
![Initial Scores by School Spending](https://github.com/LinzStearns/School_District_Analysis/blob/main/initial_scores_by_spending.png)

**Updated Scores by School Spending**
![Updated Scores by School Spending](https://github.com/LinzStearns/School_District_Analysis/blob/main/updated_scores_by_spending.png)

The data as pictured above shows that when ninth grade data was replaced, there is little to no change visible. 



*When observing Scores by school size: the data shows no change to:
*Scores by school size
*Scored by school type

### Summary

**Initial School Summary**
![Initial School Summary](https://github.com/LinzStearns/School_District_Analysis/blob/main/initial_passing_math_reading_and_overall.png)

**Updated School SUmmary**
![Updated School Summary](https://github.com/LinzStearns/School_District_Analysis/blob/main/updated_passing_math_reading_overall.png)

As pictured aboev, The most notable findings of this analysis showcase how replacing reading and math scores for ninth graders at Thomas High School with NaNs are concentrated at the individual school level. The data clearly shows that the **Average Math Score**, **Average Reading Score**, **% Passing Math**, **% Passing Reading**, and **% Overall Passing** took notable decreases, especially in the latter 3 categories. 
