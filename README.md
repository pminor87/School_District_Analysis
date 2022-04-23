# School District Analysis

## Overview of the School District Analysis
The primary purpose of this analysis is to clean the raw data and use exploratory analysis to display the data for grade scores and passing percentage as it relates to School Spending, School Size, and School Size.
 
## Results
### How is the District Summary affected?
#### After Cleaning the data and removing the invalid scores:
- Average Math Score decreased by 0.1%
- Average Reading Score was unaffected
- % Passing Math decreased by 0.2%
- % Passing Reading decreased by 0.3%
- % Overall Passing decreased by 0.01%

#### Invalid District Summary Data
![Invalid District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Invalid%20District%20Summary%20Data.PNG)

#### Clean District Summary Data
![Clean District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Clean%20District%20Summary%20Data.PNG)




### How is the School Summary affected?
#### After Cleaning the data and removing the invalid scores, Thomas High School:
- Average Math Score decreased by 0.07%
- Average Reading Score increased by 0.05%
- % Passing Math decreased by 0.09%
- % Passing Reading decreased by 0.3%
- % Overall Passing decreased by 0.3%

#### Invalid District Summary Data
![Invalid District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Invalid%20School%20Summary%20Data.PNG)

#### Clean District Summary Data
![Clean District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Clean%20School%20Summary%20Data.PNG)





### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### After Cleaning the data and removing the invalid scores, Thomas High School:
- Previously ranked 7th for % Passing Math, after removing invalid data they ranked 7th. This means there was little to no affect on this percentage.
- Previously ranked 1st for % Passing Reading, after removing invalid data they ranked 3rd. This means there was a significant enough effect on this percentage to drop them by two spots in the ranking.
- Previously ranked 2nd for % Overall Passing, after removing invalid data they ranked 2nd. This means there was little to no affect on this percentage.
	
	
### How does replacing the ninth-grade scores affect the following:
#### Math scores by grade
- Math Scores Previous Rank: 3rd
- Math Scores after data clean: Last due to NaN values.
<table>
  <tr>
    <td>Invalid Math Scores by Grade</td>
     <td>Clean Math Scores by Grade</td>
  </tr>
  <tr>
    <td><img src="Resources/Invalid Math Scores by Grade.PNG" width=200 height=350></td>
    <td><img src="Resources/Clean Math Scores by Grade.PNG" width=200 height=350></td>
  </tr>
 </table>
 
 #### Reading scores by grade
- Reading Scores Previous Rank: 5th
- Reading Scores after data clean: Last due to NaN values.
<table>
  <tr>
    <td>Invalid Math Scores by Grade</td>
     <td>Clean Math Scores by Grade</td>
  </tr>
  <tr>
    <td><img src="Resources/Invalid Math Scores by Grade.PNG" width=200 height=350></td>
    <td><img src="Resources/Clean Math Scores by Grade.PNG" width=200 height=350></td>
  </tr>
 </table>





- Scores by school spending
- Scores by school size
- Scores by school type

## Summary