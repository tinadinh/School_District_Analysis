# School_District_Analysis
## Overview of the school district analysis: Explain the purpose of this analysis.
The school board discovered that the standardized test scores for the nine grade students at Thomas High School were incorrect so they requested for updated summary. The purpose of this analysis is to replace the nineth graders' math and reading scores at Thomas High School while keeping all other data associated with this student group intact by excluding the freshman reading and math scores. Thus, proceeding to analyze the rest of the data by repeating the school district analysis from Module 4 project found in PyCitySchools.ipynb. Both math and reading scores for the nineth graders were replaced with "NaN" for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall.

## Resources 
Data Source: 
- schools_complete.csv
- students_complete.csv

Software:
- Python 3.10
- Anaconda Navigator 2.1.1
- Jupyter Notebook 6.4.5

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
### How is the district summary affected?
The average math score decreased by 0.1 points while the average reading score stayed the same. The percentage of students passing math and passing reading decreased by 1%. The overall passing percentage also decreased by 1%.

![district summary](https://user-images.githubusercontent.com/33900637/145521303-5f93a76c-ead9-47cb-8f4f-53c091805ee2.png)

### How is the school summary affected?
Thomas High School moved from 2nd place overall with a passing percentage of 90% down to 8th place with an overall passing percentage of 65%.

![school summary](https://user-images.githubusercontent.com/33900637/145521316-2c7e2a97-aff6-4cec-903a-9c068af12a5b.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing ninth graders’ math and reading scores affected Thomas High School’s performance relative to the other schools in such a way that Thomas High school dropped out of the top 5 high schools in the district and Wright High School moved into the top 5 high schools in the district, however, the bottom 5 high schools was unaffected

#### Top 5 Schools
![top school](https://user-images.githubusercontent.com/33900637/145524445-ac670e5e-1dfe-40f3-b76c-9d3e5b8c1905.png)
#### Top 5 Bottom Schools
![bottom school](https://user-images.githubusercontent.com/33900637/145524453-8f2227b5-8f12-43e6-929a-dd8b24de6740.png)


### How does replacing the ninth-grade scores affect the following:
###  - Math and reading scores by grade
- Thomas High School's 9th grade class has no math or reading score data to count thus remained the same for all other schools

![math scores](https://user-images.githubusercontent.com/33900637/145521811-f290bf3d-7f90-4098-b66f-74e69385d59e.png)
![reading scores](https://user-images.githubusercontent.com/33900637/145521814-f8cfeee0-66d3-4f2e-be96-1775977da3dc.png)


###  - Scores by school spending
- It changed at the $601-650 bin by a decrease in the percentage passing math, percentage passing reading, and overall passing percentage since Thomas High School was in that spending range. 

![school spending](https://user-images.githubusercontent.com/33900637/145521725-f8eb58a8-053d-4e16-a105-762838cb35ed.png)

###  - Scores by school size
- The Medium (1000-2000) bin saw a decrease in the percentage passing math, percentage passing reading, and overall passing percentage since Thomas High School was in that school size. 

![school size](https://user-images.githubusercontent.com/33900637/145521741-327bafe4-46e9-492a-858d-0f62b18b59fa.png)

###  - Scores by school type
- The Charter schools saw a decrease in the percentage passing math, percentage passing reading, and overall passing percentage since Thomas High School was in that school type.

![school type](https://user-images.githubusercontent.com/33900637/145521763-f3f77da6-83b7-428d-bcc9-a868749e3805.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
The four changes are reflected in the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks and the funding for each student.  The average markings were slight affected but we can see the difference in funding for each students which is ~ approximately $200.  Thomas High School 2nd stop as the top school doe not change at all.
