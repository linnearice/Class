
# District School Performance Analysis
## Overview of Project
Our company Data Analysts, Inc. (“DAI”) has worked with Maria, a school district superintendent, to deliver an analysis model which the School District can use to determine individual school performance and budget implementation.
## Scope of Project
DAI worked with Maria to provide the following:
* Data points to be evaluated by breakouts (see below):
  * Budget and per student budget
  * Reading score
  * Math score
  * Percent passing (overall and by subjects: math and reading)
  * Size
  * Type

* Data Breakouts (7) to be presented by - these number references (i.e., i to vi) correspond to the results presented below:
     1. District Summary
     2. Per School Summary
     3. High and Low Performing Schools
     4. Math Scores and Reading Scores Presented by High School
     5. School Performance by Ranges of Spending Per Student
     6. School Performance by Ranges of School Size
     7. School Performance by School Type
  
After working with Maria, it was discovered the Thomas High School ("THS) ninth grade student grades were corrupted.  Therefore, the above analysis was refactored to exclude the Thomas High School ninth grade math and reading scores from the results.  Thus, some of the focus of this study was to see how this change affected the outcomes once the grades were extracted.
## Results

### i.  District Summary
An analysis of the district data which includes the corrupted data set (see chart labeled below) and which excludes the corrupted data set (see chart below "excluding" THS 9th graders) shows there is a very modest decrease in the average math score by 1 tenth (i.e., the average math score 79.0 decreased to average math score 78.9).  There was also a very slight decrease to the overall passing percent (65.2% for all students and 64.9% excluding THS 9th grader students).  At the district level, this change to exclue THS 9th graders appears to be immaterial. 

District Summary - "includes" all students
![2021-09-12 (9)](https://user-images.githubusercontent.com/35401581/132998862-b92b2fc4-8da0-4f89-968c-ffa5734cc051.png)


District Summary – “excludes” THS Ninth Graders:
![Distsrict Summary excl THS](https://user-images.githubusercontent.com/35401581/132996591-6c2205fe-6a9d-4c47-a224-831c2fdc626f.png)

### ii.  Per School Summary
By school, it is interesting that again there is no material change in THS math and reading average scores for all students versus excluding 9th graders.  It appears there was a slight decrease in the percent passing reading (a 0.3% decrease) when excluding THS ninth graders. The same holds true for the overall passing percent - a 0.3% decrease when excluding THS ninth graders.  In general terms, there was a very, very slight performance dip in the reading scores.

The chart below compares THS data presented with the first line of data showing ***"all"*** THS students and the second line of data showing ***"excluding"*** its 9th graders:
![2021-09-12 (10)](https://user-images.githubusercontent.com/35401581/133000167-2d796997-7b01-458b-98ea-c66cc072e539.png)

The chart below presents all schools within the district:

![School Summary without THS 9th](https://user-images.githubusercontent.com/35401581/132996552-abd2d2f7-be8c-4e75-a2bf-c955a03faf74.png)

### iii.  Schools Top 5 Performing and Low 5 Performing

Overall, there appears to be no change to the rank of schools based on performance.  THS remains the number 2 ranked school among the top 5 performing high schools.  The 5 low performing high schools are unchanged by excluding THS 9th graders.

Top Performing High Schools:
![Top Performing School](https://user-images.githubusercontent.com/35401581/133003488-526f1736-8970-4509-b47f-35e578acff38.png)

Low Performing High Schools:
![Low Performing School](https://user-images.githubusercontent.com/35401581/133003473-dfde2352-64ec-40c1-897e-161f73511848.png)

### iv.  Math and Reading Scores Presented by High School
Math scores excluding THS 9th graders is presented below.  The averages presented in this chart are exactly the same when comparing them with all THS students with the obvious excption of no averages (NaN) appearing for THS 9th graders (for math scores).

"Math Scores" by High School (excluding THS 9th graders):
![Math Scores excl  THS 9th (2)](https://user-images.githubusercontent.com/35401581/133001730-4bca6050-4d59-4c27-8d4a-60afe07de186.png)

Reading scores excluding THS 9th graders is presented below.  The averages presented in this chart are exactly the same when comparing them with all THS students with the obvious excption of no averages (NaN) appearing for THS 9th graders (for reading scores).

"Reading Scores" by High School (excluding THS 9th graders):
![Reading Scores excl THS 9th (2)](https://user-images.githubusercontent.com/35401581/133001732-fdbd125e-cbc0-4312-8c32-4bca8143334c.png)

### v.  School Performance by Ranges of Spending Per Student 
There appears to be no material change to school performance by ranges of per student spending size when excluding THS 9th graders.

School Performance Based on Ranges of Per Student Spending:
![Scores by Spending Bins excl  THS](https://user-images.githubusercontent.com/35401581/133002218-22099783-a389-4637-93c0-f4a7bade14fc.png)

### vi.  School Performance by Ranges of School Size
There appears to be no material change to school performance by ranges of school size when excluding THS 9th graders.  However, it does appear school performance drops in the larger high schools.

School Performance Based on Ranges of School Size:
![Scores by Size bins (2)](https://user-images.githubusercontent.com/35401581/133003979-e1fe297f-dd06-4722-9439-6d556c9ebed0.png)

### vii.  School Performance by School Type
There appears to be no material change to school performance by school type when excluding THS 9th graders. 

School Performance by School Type:
![Scores by Type Sort (2)](https://user-images.githubusercontent.com/35401581/133002384-9c63f3dc-ce29-4187-8e33-a8eabc6ce17e.png)

