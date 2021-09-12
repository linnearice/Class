
# District School Performance Analysis
## Overview of Project
Our company Data Analysts, Inc. (“DAI”) has worked with Maria, a school district superintendent, to deliver an analysis model the District can use to determine individual school performance and budget implementation.
## Scope of Project
DAI worked with Maria to provide the following:
* Data points to be evaluated by breakouts (see below):
  * Budget and per student budget
  * Reading score
  * Math score
  * Percent passing (overall and by subjects: math and English)

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
An analysis of the district data which includes the corrupted data set (see chart labeled below) and which excludes the corrupted data set (see chart below "excluding" THS 9th graders) shows there is a very modest decrease in the average math score by 1 tenth (i.e., the average math score 79.0 decreased to average math score 78.9).  However, there was a very slight decrease to the overall passing percent (65.2% for all students and 64.9% excluding THS 9th grader students).  At the district level, this change appears to be immaterial. 

District Summary - "includes" all students
![2021-09-12 (9)](https://user-images.githubusercontent.com/35401581/132998862-b92b2fc4-8da0-4f89-968c-ffa5734cc051.png)


District Summary – “excludes” THS Ninth Graders:
![Distsrict Summary excl THS](https://user-images.githubusercontent.com/35401581/132996591-6c2205fe-6a9d-4c47-a224-831c2fdc626f.png)

### ii.  Per School Summary
By school, it is interesting that again there is no material change in THS math and reading average scores for all students versus excluding 9th graders.  It appears there was a slight decrease in the percent passing reading (a 0.3% decrease) when excluding THS ninth graders. The same holds true for the overall passing percent - a 0.3% decrease when excluding THS ninth graders.  In general terms, there was a very, very slight performance dip in the reading scores.

The chart below compares only THS data presented with the first line showing all THS students the second line of data excluding its 9th graders:
![2021-09-12 (10)](https://user-images.githubusercontent.com/35401581/133000167-2d796997-7b01-458b-98ea-c66cc072e539.png)

The chart below presents all schools within the district:

![School Summary without THS 9th](https://user-images.githubusercontent.com/35401581/132996552-abd2d2f7-be8c-4e75-a2bf-c955a03faf74.png)

### iii.  Schools Top 5 Performing and Low 5 Performing


### iv.  Math and Reading Scores Presented by High School
Math scores excluding THS 9th graders is presented below.  The averages presented in this chart are exactly the same when comparing them with all THS students with the obvious excption of no averages (NaN) appearing for THS 9th graders (for math scores).

"Math Scores" by High School (excluding THS 9th graders)
![Math Scores excl  THS 9th (2)](https://user-images.githubusercontent.com/35401581/133001730-4bca6050-4d59-4c27-8d4a-60afe07de186.png)

Reading scores excluding THS 9th graders is presented below.  The averages presented in this chart are exactly the same when comparing them with all THS students with the obvious excption of no averages (NaN) appearing for THS 9th graders (for reading scores).

"Reading Scores" by High School (excluding THS 9th graders)
![Reading Scores excl THS 9th (2)](https://user-images.githubusercontent.com/35401581/133001732-fdbd125e-cbc0-4312-8c32-4bca8143334c.png)

### v.  School Performance by Ranges of Spending Per Student 
![Scores by Spending Bins excl  THS](https://user-images.githubusercontent.com/35401581/133002218-22099783-a389-4637-93c0-f4a7bade14fc.png)

### vi.  School Performance by Ranges of School Size
![Scores by Size bins](https://user-images.githubusercontent.com/35401581/133002324-9739cd84-3c73-4345-b76c-f8b44e9f3a4b.png)


### vii.  School Performance by School Type
![Scores by Type Sort (2)](https://user-images.githubusercontent.com/35401581/133002384-9c63f3dc-ce29-4187-8e33-a8eabc6ce17e.png)

