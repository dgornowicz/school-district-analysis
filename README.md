# school_district_analysis

## Overview of the School District Analysis
The purpose of this project was to replace 9th grade students at Thomas High School's grades with NaN's while the district investigates academic dishonesty. After replacing the grades with the NaN values, several analyses were conducted on the new dataset.

## Resources
- Data Source: schools_complete.csv , students_complete.csv
- Software: Python 3.7.6, Anaconda, Jupyter Notebook 

## Results
- After removing the 9th graders scores from Thomas High School, the district summary saw the following changes:
  - Average Math Score: 79.0 to 78.9
  - Average Reading Score: 81.9 to 81.9
  - Percent Passing Math: 75% to 74.8%
  - Percent Passing Reading: 86% to 85.7%
  - Percent Overall Passing: 65% to 64.9%

<img width="740" alt="mod4Challenge_img1" src="https://user-images.githubusercontent.com/102050273/178357437-6e0177b3-e48e-467b-a078-9eaa50cc3095.png">

- After removing the 9th graders scores from Thomas High School, the school summary saw the following changes:
  - Average Math Score: 83.4 to 83.4
  - Average Reading Score: 83.8 to 83.9
  - Percent Passing Math: 93.3% to 93.2%
  - Percent Passing Reading: 97.3% to 97%
  - Percent Overall Passing: 90.9% to 90.6%
  
 <img width="803" alt="mod4Challenge_img2" src="https://user-images.githubusercontent.com/102050273/178358356-660563b3-a3bf-4766-8c3e-341218aa989b.png">
 
- Replacing the 9th grade Thomas High School scores also affected:
   - Scores by school spending
   <img width="589" alt="mod4Challenge_img3" src="https://user-images.githubusercontent.com/102050273/178358744-89edbd34-7f7e-4174-a13b-fe78c4ba5ec0.png">

   - Scores by school size
   <img width="546" alt="mod4Challenge_img4" src="https://user-images.githubusercontent.com/102050273/178358794-e1d12e16-855b-4ae3-b683-37e59af27716.png">

   - Scores by school type
   <img width="512" alt="mod4Challenge_img5" src="https://user-images.githubusercontent.com/102050273/178358812-60fea9f9-5720-49f3-a949-be39d646dcb8.png">


## Summary
After the 9th grade math and reading scores for Thomas High School had been marked with NaNs, the percent passing reading went down and the percent passing math did not change. This suggests that among the 9th grade reading scores, there may be merit to the district investigating potential academic dishonesty.
