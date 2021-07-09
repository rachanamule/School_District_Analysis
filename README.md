# School District Analysis

## Overview

### Background
While working with Maria to complete the School District Analysis, The school board has notified Maria and supervisor that the data file shows evidence of academic dishonesty; specifically, math and reading grades for Thomas High School. Mostly ninth graders appear to have been altered.
  
### Purpose
Purpose of this analysis is to replace the math and reading scores with NaN for ninth grade students who are studying in Thomas High School. And once it is done repeat the school district analysis.

Deliverables of this analysis are:

* Deliverable 1: Replace ninth-grade reading and math scores

* Deliverable 2: Repeat the school district analysis

* Deliverable 3: A written report for the school district analysis (README.md) 

## Result

* How is the district summary affected?
 
    The average math and reading score decreased by 0.1 points. The overall passing percentage also decreased by 0.2%.

    Here are the reference images:
  
    District Summary Before:
  
    ![District Summary Before](https://github.com/rachanamule/School_District_Analysis/blob/b2772ae0ff13918c1db14656907e3e4ea2751f8e/Resources/district_summary_before.png)
  
    District Summary After:
  
    ![District Summary After](https://github.com/rachanamule/School_District_Analysis/blob/e3d29fd206a0dbd4dfd637204734229fe5a059a6/Resources/district_summary_after.png)



* How is the school summary affected?

    The only change in data is with Thomas High School. The overall math and reading passing numbers decreased slightly.
    The over all passing for Thomas High School was 90.94% before , with the 9th graders data cleanup the overall passing reduced by 0.3% which now shows 90.63%.
  
    ![Per school summary](https://github.com/rachanamule/School_District_Analysis/blob/c94a9d58e4cfe45a71272134ecc5a990db5edba2/Resources/per_school_summary_after.png)

* How does replacing the ninth graders math and reading scores affect Thomas High School’s performance relative to the other schools?

    Replacing the ninth graders math and reading scores by NaN has not affected the performance drastically. There is only slight difference in ovarall percentage which is negligible.


* How does replacing the ninth-grade scores affect the following:

	* Math and reading scores by grade
	    
      The only difference now between the scores is that under 9th graders who attended Thomas High School it shows an nan.
    
      Math and Reading Scores by Grades
     
      ![math and reading scores by grades](https://github.com/rachanamule/School_District_Analysis/blob/62174c7af39873cb94b002dbfcea0d0e50d366d9/Resources/math_and_reading_score.png)
     
  * Scores by school spending
	
	   The score stays nearly same even though the 9th graders data is replaced as null.
   
    ![Scores by School Spending](https://github.com/rachanamule/School_District_Analysis/blob/caed0cc1a7e8dbad14361a09a8d76694be98c432/Resources/scores_by_school_spending.png)
  
  * Scores by school size
	
	  There is very slight change of 0.1 or 0.2 but rounded values shows no change. So replacing the 9th grade data does not affect drastically. 
    
    ![Scores by school size](https://github.com/rachanamule/School_District_Analysis/blob/caed0cc1a7e8dbad14361a09a8d76694be98c432/Resources/scores_by_school_size.png)

  * Scores by school type
	 
	   Scores by school type remains same.
    
    ![Scores by school type](https://github.com/rachanamule/School_District_Analysis/blob/caed0cc1a7e8dbad14361a09a8d76694be98c432/Resources/score_by_school_type.png)


Result of Deliverable 1 : Math and Reading scores replaced by NAN for students of Thomas High School ninth graders.

![Deliverable 1](https://github.com/rachanamule/School_District_Analysis/blob/61f6f104bc37ab0d615af381246451d31c1da927/Resources/Deliverable_1.png)

## Summary

Updating the ninth-grader data from Thomas High School for math and reading score does not make a big difference. 

Summary of changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Student count is reduced from 39170 to 38709

2. Overall student passing math and reading count is reduced from 25528 to 25105

3. So the overall passing percentage for district summary is reduced to 64.8% from 65.1%.

4. Overall passing percentage for district summary is reduced to 90.63% from 90.94%.
 
