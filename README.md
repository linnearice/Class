
# District School Performance Analysis
## Overview of Project
Our company Data Analysts, Inc. (“DAI”) has worked with Maria, a school district superintendent, to deliver an analysis model the District can use to determine individual school performance and budget implementation.
## Scope of Project
DAI worked with Maria to provide the following:
1.	Data points to be evaluated by breakouts (see below):
a.	Budget and per student budget
b.	Reading score
c.	Math score
d.	Percent passing (overall and by subjects: math and English)
2.	Data Breakouts to be presented by:
a.	District Summary
b.	Per School Summary
c.	High Performing Schools
d.	Low Performing Schools
e.	Math Scores Presented by High School
f.	Reading Scores Presented by High School
g.	School Performance by Ranges of Spending Per Student 
h.	School Performance by Ranges of School Size
i.	School Performance by School Type
After working with Maria, it was discovered the Thomas High School ("THS) ninth grade student grades were corrupted.  Therefore, the above analysis was refactored to exclude the Thomas High School ninth grade math and reading scores from the results.  Thus, some of the focus of this study was to see how this change affected the outcomes once the grades were extracted.
## Results

### District Summary
An analysis of the district data which includes the corrupted data set (see chart labeled below) and which excludes the corrupted data set (see chart below "excluding" THS 9th graders) shows there is a very modest decrease in the average math score by 1 tenth (i.e., the average math score 79.0 decreased to average math score 78.9).  However, there were very slight and overall no significant changes to the percent passing measurements.  At the district level, there are no material changes from excluding the corrupted data. 

District Summary - "includes" all students
![2021-09-12 (9)](https://user-images.githubusercontent.com/35401581/132998862-b92b2fc4-8da0-4f89-968c-ffa5734cc051.png)


District Summary – “excludes” THS Ninth Graders:
![Distsrict Summary excl THS](https://user-images.githubusercontent.com/35401581/132996591-6c2205fe-6a9d-4c47-a224-831c2fdc626f.png)

### Per School Summary
By school, it is interesting that again there is no material change in THS math and reading average scores for all students versus excluding 9th graders.  That is not the case though with the passing percentages.  These data points saw a distint increase in passing percentages. For example, the overall passing percentage increased from 64.9% (includes all THS studetns) to 90.6% (excludes 9th grade THS students).  Evaluating these changes changes the landscape of THS's performance to a high performing school. 


The chart below compares only THS data presented with the first line showing all THS students the second line of data excluding its 9th graders:
![2021-09-12 (10)](https://user-images.githubusercontent.com/35401581/133000167-2d796997-7b01-458b-98ea-c66cc072e539.png)



The chart below presents all schools within the district:

![School Summary without THS 9th](https://user-images.githubusercontent.com/35401581/132996552-abd2d2f7-be8c-4e75-a2bf-c955a03faf74.png)

 
### Reading Scores Presented by High School
### School Performance by Ranges of Spending Per Student 
### School Performance by Ranges of School Size
### School Performance by School Type

