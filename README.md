# School_District_Analysis

## Overview of School District Analysis

### Purpose
  For this project, the school board has notified Maria and her supervisor that the reading and math grades for Thomas High School(THS) are suspect and may have been altered. The goal of this analysis is to update the data analysis already completed so that the values associated with 9th grade reading and math scores are updated with NaNs. This will prevent the tampered scores from skewing the results. 
  
## School District Analysis Results

* Total Students did not change. When calculating the % passed scores for math and reading, we did use a modified count that did not include the 461 9th grade students from THS. 
* Total budget and total number of schools did not change. 
* Average math score decreased from 81.87784 to 81.85579.
* Average reading score decreased from 78.98537 78.93053.
* Percentage of students who passed math decreased from 74.98085 to 74.76039.
* Percentage of students who passed reading decreased from 85.80546 85.65967.
* Overall passing percentage decreased from 65.17236 to 64.85572.


## School District Analysis Summary

The largest changes to the data are seen in looking at data summarized at the school level and the grade level and focusing on THS and the 9th grade. When looking at the THS ninth grade reading scores you now seen NaN instead of 83.72885. When looking at te THS ninth grade math scores, you now see NaN instead of 83.59002.

Math Scores, updated : ![image](https://user-images.githubusercontent.com/103475613/167325317-6d81a54d-ee63-4e85-9bdf-f6aea53a4915.png)

Reading Scores, updated : 
![image](https://user-images.githubusercontent.com/103475613/167325302-292ce48d-4b9d-4e70-9e27-a6fa9f61b90e.png)

Another important thing to note is in the slight changes to the data that is grouped by spending ranges by student and school size. THS has 1635 total students and a per student budget of $638.00. By excluding the scores, the average scores in the Medium (1000 - 1999) school size and $631 - 645 spending per student groupings went down slightly. When rounding to the nearest tenth, you will not see these differences as they are very minor.

Spending Ranges, updated, not rounded:
![image](https://user-images.githubusercontent.com/103475613/167326148-9905a4b9-9ee3-4954-a045-ed3be0e46d15.png)


School Size, updated, not rounded:
![image](https://user-images.githubusercontent.com/103475613/167326157-581e0d28-afbf-496b-b6a9-e10b436ed8dc.png)



