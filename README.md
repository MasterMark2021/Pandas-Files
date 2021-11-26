# School District Analysis

## Project Overview

The purpose of this project is to analyze the data of an School District, such as student grades and funding, to learn new insights and visually provide clear results on each school's performance. #Signed

---
## Resources

*Resources:* All data used in this analysis is found inside of the Resources folder(https://github.com/MasterMark2021/School_District_Analysis/tree/main/Resources)
**Software:** Python 3.8, Anaconda, Jupyter Notebook. #Signed

## Results
Due to potential academic irregularity observed for the ninth grade students of Thomas High School, this analysis was conducted twice. The first analysis included the full set of student data. In the second  analysis, the ninth grade students of Thomas High School had their scores omitted from the analysis. The ninth grade class of Thomas High School have had their scores misplaced with NaN. The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN. #Signed

- Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:
  - The overall passing percentage for Thomas High School fell to 65%
  - The overall passing percentage for the entire district fell to 64.9%
  - Thomas High School was no longer included on the list of top five schools. #Signed

- When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
  - The overall passing percentages of Thomas High School decreased by 0.11%
  - The average scores of Thomas High School for math and reading *increased* by 0.06
  - For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%. #Signed


# The Effects of School Budget and School Size
It is found that Average Scores and Passing Percentages do not increase as spending per student increases. The top performing school in the entire district (Cabera High School) received $68 *less* per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores. #Signed
 
When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible. All District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings. #Signed

# Charter vs. District Schools
Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. As seen in the DataFrame below, **Charter schools have a 36% higher overall passing percentage** than District schools. #Signed


# Average Scores by Grade Level
After analyzing the average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. The average scores within each school only varries by 1-2% depending on grade level. However, the difference in scores is more apparent when comparing different schools. #Signed

# Summary
However, it is not possible to determine the extent of the potential academic irregularity to exclude from the dataset. As a consequence of this, the entire ninth grade of students from Thomas High School have had their scores misplaced from the results. #Signed

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to drop. The district as a whole has also had its average math and reading scores decrease.Thomas High School lost its place as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. To view the full script, please open PyCitySchools_Challenge.ipynb in Jupyter Notebook.

*Author: Mark Okoli*  
