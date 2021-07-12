# School Testing Analysis 

## Project Overview
Upon learning news of potential academic dishonesty with Thomas High School ninth-graders, this analysis will exclude all Thomas High School ninth-graders. The analysis will be conducted again without these students and compared to the original analysis. 

## Results

* How is the district summary affected? 
  * Since a total of 461 ninth graders, we removed from the total of 39,170 which is 1.18%, it did not meaningfully alter the district summary.

* How is the school summary affected? 
  *  Just like the district summary, the school summary did not meaningfully change.

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
  * Removing the 9th-grade score took Thomas High School from 8th place to 2nd place by an overall passing score

The left screenshot is the original dataframe and the right screenshot is the updated dataframe removing all Thomas High School ninth-graders:

<img src="https://raw.githubusercontent.com/hdolci/school-district-analysis/main/Resources/original_per_school_summary_before_REPLACE.png" width="50%" height="50%"/><img src="https://raw.githubusercontent.com/hdolci/school-district-analysis/main/Resources/original_per_school_summary_after_REPLACE.png" width="50%" height="50%"/>


* Just like the district and school summary, the following data points had little change after removing Thomas High School ninth-graders: Math and reading scores by grade, Scores by school spending, Scores by school size, & Scores by school type

## Summary of results

Summary: 

By removing the ninth graders from Thomas High School(replacing their scores with NaN), we found an increase in scores for Thomas High School:

* Average Reading Score 66.9 to 83.8
* % Passing Math: 66.91% to  93.18%
* % Passing Reading: 69.66% to 97.01%
* % Overall passing: 65.08% to 90.63%

Based on these drastic changes, we should consider further investigate the issue with the 9th-grade scores or possibly have them retake the exam.
