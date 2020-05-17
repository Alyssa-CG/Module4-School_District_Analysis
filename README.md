# School District Analysis

## Project Overview

Math and reading scores for were analysed and compared for 15 high schools. Upon completion of the analysis, it was discovered that a select group of scores, specifically those of the 9th graders in Thomas High School, were tampered with and the decision was made to remove all the affected scores. Below findings are of the changes caused by that removal.

## Resources

* Data Source: 
  * schools_complete.csv
  * students_complete.csv
* Software:
  * Python 3.7.7
  * Jupyter Notebook 6.0.3
  * Anaconda 1.7.2
  * Conda 4.8.3

## Summary of Findings


#### District Summary
The district summary was slightly changed by the removal of Thomas High School's 9th graders grades, as shown in the charts below.

##### District Summary before Thomas High School was removed
![District Summary Before](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/DistrictSummarybefore.png)

##### District Summary before Thomas High School was removed
![District Summary After](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/DistrictSummaryafter.png)

As visible from the dataframes, the average math score, the percentage of students passing math, the percentage of students passing reading and the percentage of students passing both math and reading all fall slightly without Thomas High School 9th graders' scores.

#### School Summary

##### School Summary after Thomas High School was removed

![School Summary After](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/School%20Summary%20after.png)

Data for all other schools remain unchanged, but while average math and reading scores stayed almost the same for Thomas High School, the percentages of their students passing math, reading or both fell drastically, from 93%, 97% and 91% to 67%, 70% and 65% respectively.

#### High and Low performing Schools

##### Top performing High Schools
![Top Schools before](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/Top%20Schools%20before.png)

In our initial analysis, as shown above, Thomas High School was ranked as one of the top five best performing high schools in the district. Replacing their scores affects their performance by dropping their performance so they are no longer in the top five. Instead, we can see now that Wright High School is a top performer.

The overall low performing school were unaffected. Performance was evaluated based on the percentage of students passing both reading and math, so although the percentage of students passing each subject and both had fallen for Thomas High School,the percentage of students passing both was still not as low as the percentage in the lowest performing schools.

#### Math and Reading Scores by Grade

##### Reading Scores by Grade after Removal of Thomas High School 9th grade scores
![Reading Scores by Grade After](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/Reading%20Scores%20by%20Grade%20after.png)

The removal of the scores for Thomas High School 9th graders only affects the Thomas High School 9th graders scores for reading and math, by replacing the averages with "nan" as shown above. No other scores were affected.

#### Scores by School Spending

Scores by school spending were only affected in the category to which Thomas High School belonged, the $630-$640 per student budget bin. In this group, the percentage passing math, reading or both fell from 73%, 84% and 63% to 67%, 77% and 56% respectively.

#### Scores by School Size

Only data for the size that applies to Thomas High School was affected by the change. While Average Math and Reading scores remained the same as before, the percentage of students passing math, reading or both subjects fell from 94%, 97% and 91% to 88%, 91% and 85% respectively.

#### Scores by School Type

##### Scores by School Type after removal of Thomas High School
![Scores by School Type After](https://github.com/Alyssa-CG/Module4-School_District_Analysis/blob/master/Images/Scores%20by%20School%20Type%20after.png)

Again, data is only affected for the category to which Thomas high school belongs, Charter schools. Average Math and Reading scores for Charter School students remained the same as before, but the percentage of charter school students passing math, reading or both subjects fell from 94%, 97% and 90% to 90%, 93% and 87% respectively.


## Conclusion

Much of the school data was unaffected by replacing the compromised data with NumPy's NaN function, but most of the averages affected by it decreased.
