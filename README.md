# School District Analysis

## Using Jupyter Notebook and Pandas to analyze district-wide standardized test data

## Overview

Maria, the chief data scientist for a city school district, approached us to help her with the analysis, reporting, and presentation
of standardized test data for the district. After our initial analysis was completed, the school district uncovered evidence of 
academic dishonesty that had affected the scores of the ninth graders at Thomas High School, and we were tasked with finding and 
removing the affected data, and then repeating our overall analysis to revise the district-wide data. 

## Results

### How is the district summary affected?

- The district-wide scores were largely unaffected by the removal of the Thomas High ninth graders. Though the district-wide passing rates
for reading, math, and overall were slightly lower, it was by 2 to 3-tenths of a percentage point. The number of Thomas High scores 
removed was 461 total, out of the initial sample of 39,170 students district-wide, just 1.2% of the total initial sample. 

![Initial District Summary](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Initial_District_Summary.png)
![Updated District Summary](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Updated_District_Summary.png)

### How is the school summary affected?

- Average reading score for Thomas High School went down by half a point, while the average math score went up by just under half a point. 
The passing percentages for reading, math, and overall were down, but by less than one percent. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- Though the overall performance by Thomas High School dropped slightly with the removal of the ninth graders' scores, Thomas High maintained the 
second highest overall performance by percent students passing both math and reading among the high schools in the district.

![Top Schools Initial](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Top_Schools_Initial.png)
![Top Schools Updated](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Top_Schools_Updated.png)

Math and reading scores for ninth graders across the district were slightly affected by the removal of the Thomas High students, with both the
math and reading scores dropping. The math scores dropped by .23 points, and reading score dropped by .09 points. 

### Scores by school spending

- Scores based on school spending per student were unchanged. 

![Score By Per Student Spending Initial](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Initial_Spending_per_Student.png)
![Score By Per Student Spending Updated](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Updated_Score_By_Spending.png)

### Scores by school size

- Scores by school size were unchanged.

![Scores By School Size Initial](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Intial_Scores_By_School_Size.png)
![Scores By School Size Updated](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Updated_Scores_By_Size.png)

### Scores by school type

- Scores by school type were unchanged.

![Initial Score by School Type](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Initial_Score_By_Type.png)
![Updated Score by School Type](https://github.com/greensleeves8/School_District_Analysis-/blob/master/Resources/Updated_Score_By_Type.png)

## Summary

The biggest changes with the removal of the test scores for the Thomas High School ninth graders were the following:

- Reading score for Thomas High School dropped slightly.
- Math scores for Thomas High School rose slightly, though the overall rate of passing dropped, along with the reading passing rate. 
- Ninth grade math and reading scores dropped slightly district-wide.
- District-wide reading, math, and overall passing rates dropped slightly. 
