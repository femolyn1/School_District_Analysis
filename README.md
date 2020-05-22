# School_District_Analysis

## Project Overview:
Analysis of data on student finding and student test scores to showcase trends in school performance which will assist the school board in making decisions regarding school budget and priorities. A district  school summary with the following information is required:
1. Total number of students 
2. Total number of schools
3. Total budget
4. Average math score
5. Average reading score
6. Percentage of student who passed math
7. Percentage of student who passed reading
8. Overall passing percentage

In addition to the above, a school summary with the following information is also required:

1. School name
2. School type
3. Total student
4. Total school budget
5. Per student budget
6. Average reading score
7. Percentage passing math
8. Percentage passing reading
9. Percentage overall passing

We are also required to aggregate and analyze the student scores by school spending, school size and school type. 

## Resources:
Data Source: School_ District_Analysis.csv; Software: Python 3.7.6;  Jupyter Notebook 

## Challenge Summary

### District summary comparison after replacing the 9th grade scores of Thomas High School with NaN:

* The percentage passing math reduced from 75% to 74% 

* The percentage passing reading dropped from 86% to 85% 

* The percentage overall passing also reduced from 65% to 64%

As shown above, the removal of the 9th grade scores had a slight impact on the percentage passing math and reading and the percentage overall passing.

### School summary comparison after replacing the 9th grade scores of Thomas high school with NaN:

* % passing Math and Reading before removing 9th grade scores for Thomas High School; 93.27 % and 97.30%
* % passing Math and reading after removing 9th grade scores for Thomas high School: 66.9% and 69.6%
* Overall passing percentage before removing the 9th grade scores of Thomas high school: 90.94%
* Overall passing percentage after removing the 9th grade score: 65%
From the above information, we can see that the removal of the 9th grade scores for Thomas High school had a significant impact on the scores. 

### Effect of Thomas High School 9th grade score removal on Thomas High School performance relative to other schools. 

After removing the 9th grade scores, Thomas high school dropped from the second position among the top 5 schools to the eight position. So the removal had a significant impact on the schools performance. 

### Effect of Thomas high School 9th grade score removal on Math and Reading score by grade:

Jupyter notebook displayed NaN for both Math and reading scores of Thomas High school after removing the 9th grade scores . This is an expected output and it explains the reason for the significant drop in Thomas High School performance.

### Effect of Thomas High School 9th grade score removal on scores by school spending

Overall passing spending range $645 to $675 reduced from 63% to 56% . 

### Effect of Thomas High School 9th grade score removal on school size

Although the average math and reading scores were not affected , the % passing Math , Reading and % Overall passing for school were affected due to the removal of Thomas High school 9th grade scores. Before the removal , the % passing math, reading and overall passing within the medium range (1000- 2000)  were 94, 97 and 91 and these reduced to 88, 91 and 85 respectively after the removal.

### Effect of Thomas High School 9th grade score removal on school type

Since Thomas High School falls within the Charter school type, the District school output was not affected by the score removal. However, the Charter type school information was affected. The % passing math, reading and % overall passing within the charter type school before the score was removed were 94%, 97% and 90% respectively . After the removal, the scores reduced to 90%, 93% and 87%.





