# School District Analysis

## Overview of the School District Analysis
The primary purpose of this analysis is to clean the raw data and use exploratory analysis to display the data for grade scores and passing percentage as it relates to School Spending, School Size, and School Type.
 
## Results
### How is the District Summary affected?
#### After Cleaning the data and removing the invalid scores:
- Average Math Score decreased by 0.1%
- Average Reading Score was unaffected
- % Passing Math decreased by 0.2%
- % Passing Reading decreased by 0.3%
- % Overall Passing decreased by 0.01%

<space>

#### Invalid District Summary Data
![Invalid District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Invalid%20District%20Summary%20Data.PNG)

#### Clean District Summary Data
![Clean District Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Clean%20District%20Summary%20Data.PNG)

<space>

### How is the School Summary affected?
#### After Cleaning the data and removing the invalid scores, Thomas High School:
- Average Math Score decreased by 0.07%
- Average Reading Score increased by 0.05%
- % Passing Math decreased by 0.09%
- % Passing Reading decreased by 0.3%
- % Overall Passing decreased by 0.3%

#### Invalid District Summary Data
![Invalid School Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Invalid%20School%20Summary%20Data.PNG)

#### Clean District Summary Data
![Clean School Summary Data](https://github.com/pminor87/School_District_Analysis/blob/main/Resources/Clean%20School%20Summary%20Data.PNG)

<space>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### After Cleaning the data and removing the invalid scores, Thomas High School:
- Previously ranked 7th for % Passing Math, after removing invalid data they ranked 7th. This means there was little to no affect on this percentage.
- Previously ranked 1st for % Passing Reading, after removing invalid data they ranked 3rd. This means there was a significant enough effect on this percentage to drop them by two spots in the ranking.
- Previously ranked 2nd for % Overall Passing, after removing invalid data they ranked 2nd. This means there was little to no affect on this percentage.

<space>

### How does replacing the ninth-grade scores affect the following:
#### Math scores by grade
- Math Scores Previous Rank: 3rd
- Math Scores Rank after data clean: Last, due to NaN values.
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
 
 <space>
 
 #### Reading scores by grade
- Reading Scores Previous Rank: 5th
- Reading Scores Rank after data clean: Last, due to NaN values.
<table>
  <tr>
    <td>Invalid Reading Scores by Grade</td>
     <td>Clean Reading Scores by Grade</td>
  </tr>
  <tr>
    <td><img src="Resources/Invalid Reading Scores by Grade.PNG" width=200 height=350></td>
    <td><img src="Resources/Clean Reading Scores by Grade.PNG" width=200 height=350></td>
  </tr>
 </table>

<space>

#### Scores by school spending ("$631-645")
- Average Math Score decreased by 0.02%
- Average Reading Score increased by 0.01%
- % Passing Math decreased by 0.02%
- % Passing Reading decreased by 0.07%
- % Overall Passing increased by 17.2%

<space>

#### Scores by school size ("Medium (1000-1999)")
- Average Math Score decreased by 0.01%
- Average Reading Score decreased by 0.01%
- % Passing Math decreased by 0.02%
- % Passing Reading decreased by 0.06%
- % Overall Passing decreased bu 0/46%

<space>

#### Scores by school type ("Charter")
- Average Math Score decreased by 0.01%
- Average Reading Score was unaffected
- % Passing Math decreased by 0.01%
- % Passing Reading decreased by 0.04%
- % Overall Passing increased by 4.65%

<space><space>
<space><space>

## Summary
#### Four noteworthy changes that took place after cleaning the data were:
- For the most part there was a small decrease in score performance for Thomas High School in all five categories.
- Their rankings against other schools decreased for everything except "% Overall Passing".
- Their rankings for 9th graders for math and reading scores went from 3rd and 5th respectively, to last for both due to the NaN values.
- One interesting piece of data was that their average Reading score increased by 0.05% after cleaning the data which may mean that the 9th grade students that cheated were not very good at it.