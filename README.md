# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.
The purpose of the school district analysis is to find the evidence that the reading and math grades for Thomas High School ninth graders changed. The school board needed to know the extend of this dishonesty so they ask to find any evidence.  They request to exclude the freshman reading and math scores by replacing them with NaNs entries and proceed analyzing the rest of the data by repeating the school district analysis from Module 4 project found in PyCitySchools.ipynb.

## Resources 
Data Source: 
- schools_complete.csv
- students_complete.csv
Software:
- Python 3.6.10
- Anaconda Navigator 2.1.1
- Jupyter Notebook 6.4.5

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
### How is the district summary affected?
Comparing the two chart above the average show the difference when the 9th grade student Math and Reading scores from Thomas High Schools were excluded from the District Summary.  Excluding the Thomas High Schools 9th grade students Reading and Math scores slightly affected by tenths of average scores in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing.  The overall slight decrease in averages do not change but it will affect the following summaries.

### How is the school summary affected?
School Summaries with or without Thomas High School
In the charts above, the difference when excluding the Thomas High Schools 9th grade students Reading and Math scores is slight.  In this charts, the Thomas High School scores without the 9th, slight decrease, for example in % Overall Passing from 90.948012 to 90.630324.  Comparing Thomas High School % Overall Passing placement does not change much either.  They are still the within the 90 percentile passing.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools does not affect their % Overall Passing mark.  They are still within within the 90 percentile passing mark.

### How does replacing the ninth-grade scores affect the following:
###  - Math and reading scores by grade
- Excluding the ninth graders’ math and reading scores from  Thomas High School’s only change slightly and Thomas High School still holding the 2nd Top Five Schools in the district.
###  - Scores by school spending
- Excluding the ninth graders’ math and reading scores from  Thomas High School’s affected their spending per student from $638.00 to $888.53.
###  - Scores by school size
- The scores by school size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School
###  - Scores by school type
- The scores by school type size is also slightly affected by excluding the ninth graders’ math and reading scores from  Thomas High School.


## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
The four changes are reflected in the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks and the funding for each student.  The average markings were slight affected but we can see the difference in funding for each students which is ~ approximately $200.  Thomas High School 2nd stop as the top school doe not change at all.
