# School_District_Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

The data provided for this analysis included csv files containing information about schools and students.  In total, there were 15 schools and the csv file identified the type of school, number of students, and budget.  The type of school provided information about if the school was a district or charter school. The student csv file included information about the students such as name, grade, school, as well as each student's reading and math scores.  

For this analysis, it is worth noting that there are differences between district schools and charter schools.  These differences lead to different standards for academics, programs, as well as admissions.  The funding for the school also does not come from the same source.  I believe that it is important to recognize these differences and understand that comparing district schools to charter schools is not entirely apples to apples.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

##### How is the district summary affected?
* The distric summary was slightly affected when removing the test scores for 9th grade at Thomas High School.  The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 231843](https://user-images.githubusercontent.com/107599510/181419395-dbd359d2-b25a-4f94-8ad3-73b801f168b8.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 231232](https://user-images.githubusercontent.com/107599510/181418764-9935a9d1-ff21-48fc-ad0e-e1c841a2e0e3.png)

* The average math score was affected slightly by removing the ninth grade scores going from 79% to 78.9%.  The average reading score was not impacted from a rounded percentage standpoint as both scores were 81.9%.  As expected, the passing math, passing reading, and overall percent passing dropped slightly after removing the 461 9th grade scores from Thomas High School.

##### How is the school summary affected?

* Looking at the top five schools, Thomas High School scored in second place with and without the test scores included in the summary.  The following chart shows the results with all scores counted in the summary:

![Screenshot 2022-07-27 233217](https://user-images.githubusercontent.com/107599510/181420997-969cdc8d-aa85-4040-a706-40804ad8eda9.png)

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

![Screenshot 2022-07-27 233537](https://user-images.githubusercontent.com/107599510/181421396-bff19c65-fc71-45f5-9d5f-74c9f32130be.png)

The overall passing percentage changed slightly from 90.94% to 90.63% after the ninth grade test scores were removed.

##### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* The following chart shows the results with all scores counted in the summary:

* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

##### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade

* The following chart shows the results with all scores counted in the summary:


* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

##### Scores by school spending

* The following chart shows the results with all scores counted in the summary:


* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

##### Scores by school size

* The following chart shows the results with all scores counted in the summary:


* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

##### Scores by school type

* The following chart shows the results with all scores counted in the summary:


* The following chart shows the results with all of the 9th grade scores removed from Thomas High School:

##### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
