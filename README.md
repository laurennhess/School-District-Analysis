# School District Analysis

## Overview
### Background
#### The school board found evidence in the students_complete.csv file of academic dishonesty amongst ninth graders at Thomas High School for math and reading grades. 

### Purpose
#### The purpose of this analysis is to omit any instances of academic integrity amongst ninth graders at Thomas High School. By viewing the csv file as data frames, student and school, we are able to compare the math and reading grades of ninth grade students at Thomas High School with ninth grade students from other high schools in the state. It is extremeley important to assess and omit any instances of dishonesty to uphold the state-testing standards for math and reading. From the data frames, we are able to obtain all math and reading test scores from each student at each highschool and replace all Thomas High ninth graders grades with NaNs while keeping the rest of the data intact. 

## Results
### Affect on District Summary 
#### After we removed all math and reading scores of ninth graders from Thomas High School, there are slight changes in our district summary data frame.
![Screen Shot 2022-01-07 at 7 05 04 PM](https://user-images.githubusercontent.com/94096530/148629413-4b265109-bc96-40f5-96a2-645da095730d.png)
#### We can see that the number of total students drops from 39,170 to 38,709 students, meaning there are a total of 461 ninth grade students at Thomas High School whose grades were omitted. The total budget was unaffected. The Average Math Score, Average Reading Score, % Passing Math, and % Passing Reading remained the same. However, the overall passing percentage decreased.  

### Affect on School Summary
![Screen Shot 2022-01-07 at 7 17 13 PM](https://user-images.githubusercontent.com/94096530/148629732-9e63117c-ea2e-47df-a823-0b91d8ef598e.png)
#### After we removed all math and reading scores of ninth graders from Thomas High School, there are significant changes in the school summary data frame for Thomas High School Only. Their overall passing score significantly decreases since the falsified scores of 461 students will no longed be considered in the overall passing score. Since there was such a significant change in the overall passing percentage, it is clear that there was academic dishonesty amongst the ninth grade scores. 

### Affect on Thomas High School's Overall Performance
![Screen Shot 2022-01-07 at 7 20 56 PM](https://user-images.githubusercontent.com/94096530/148629845-f71de1be-4935-4e8a-b22a-01d37e623a93.png)
#### When we only take into account the math and reading scores for students in 10th - 12th grade at Thomas High School, we can see that the overall passing rate is amongst the top five in the district, pulling in at number two. From this, we can see that with the ninth grade scores omitted, Thomas High school is a high performing school. However, because we can not assess the scores of ninth graders in the overall passing performance, it looks like Thomas High School is performing better on standardized testing than other schools in the state. 

### Affect on Ninth Grade Scores 
#### Math and Reading Scores by Grade
###### Average Math
![Screen Shot 2022-01-07 at 7 25 31 PM](https://user-images.githubusercontent.com/94096530/148629964-b8581ee1-923c-40ac-9726-ba6ce3f19026.png)
###### Average Reading
![Screen Shot 2022-01-07 at 7 27 11 PM](https://user-images.githubusercontent.com/94096530/148630026-1eb70dc2-2029-4539-aea5-0c506e2a5f63.png)
##### When Thomas High School grades are negated for ninth graders, it does not have an affect on math and reading scores for other grades at Thomas High School or other schools in the district.

#### Scores by School Spending
![Screen Shot 2022-01-07 at 7 28 15 PM](https://user-images.githubusercontent.com/94096530/148630056-0c2e32e5-8baa-419a-8ef4-7ed0f53155d2.png)
##### When Thomas High School grades are negated for ninth graders, the scores based on school spending does not change the data frame. The average reading and math scores do not change, and neither does the percentage rates.

#### Scores by School Size 
![Screen Shot 2022-01-07 at 7 30 10 PM](https://user-images.githubusercontent.com/94096530/148630109-4c243593-fc93-4492-bc67-d480c27e637a.png)
##### When Thomas High School grades are negated for ninth graders, the scores based on school size do not change the data frame. The average reading and math scores, as well as the passing percentage rates does not change. 

#### Scores by School Type
![Screen Shot 2022-01-07 at 7 31 07 PM](https://user-images.githubusercontent.com/94096530/148630127-d226082c-d8cd-4bb8-b1f3-ef78b1990381.png)
##### When Thomas High School grades are negated for ninth graders, the scores based on school type do not change the data frame. The average reading and math scores, as well as the passing percentage rates do not change. 

## Summary 
### There are four major changes to the school district summary analysis when we omit the math and reading scores of ninth graders at Thomas High School. First, the overall passing rate in the school district data frame significantly decreases since the academic dishonesty caused the ninth graders scores to be so high. This validated the recognition of academic dishonesty. The second major change was the number of total students in the district. Removing the ninth graders from Thomas High School decreased the overall student count by 461 students. The third major change was in the school summary data frame. In the school summary data frame, we see that the overall passing percentage of Thomas High School increases dramatically when the ninth grade scores were negated. The last major change was when we only accounted for students in 10th - 12th grade at Thomas High School. Since there was a reduction in students accounted for, the overall performance of Thomas High School increased since their student population was reduced, causing them to jump into the top five schools in the district. 
