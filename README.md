# school-district-analysis
Module 4 of UCB Data Science Bootcamp - PyCitySchools w/ Jupyter Notebook and Anaconda

### Overview of School District Analysis
The main purpose of this analysis is to determine how omitting the grades of 9th graders from Thomas High School affects the calculated totals and averages of test results and passing % in county totals and various slices and breakdowns.


### Results
The overall analysis appears to be unaffected by omitting 9th grader test data from Thomas High School. The totals and average across all categories appear to only shift by a fraction of a percent, and do not affect the overall results of the analysis.

Result Details:
* **District Summary** - The district summary appears to be virtually unaffected by the changes. Only the Math Score appears to go down by 0.1%, the rest of the scores appear unaffected. 
    * ![Overall District DF - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_district_summary_before.png)
    * ![Overall District DF - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_district_summary_after.png)

* **School Summary** - The overall passing percentage for Thomas High School does not seem to be impacted (when rounded to the nearest percent). The Overall % Passing Score drops by 0.3%, which is not enough to bump the score down by a whole percent. 
    * ![THS Summary - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_summary_before.png)
    * ![THS SUmmary - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_summary_after.png)

* **Relative Performance** - The relative standing of the schools is not impacted, since the % Overall Passing remain unchanged when rounded to nearest percent (see School Summary above).

* **Math and Reading Score by Grade** - The math and reading scores for Thomas High School are omitted, but this omission does not have a large impact on the average for the school overall since the averages for 9th grade are very close to the averages for grades 10-12.
    * ![Math Scores by Grade - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_math_scores_df_before.png)
    * ![Math Scores by Grade - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_math_scores_df_after.png)
    * ![Reading Scores by Grade - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_reading_scores_df_before.png)
    * ![Reading Scores by Grade - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_reading_scores_df_after.png)

* **Scores by School Spending** - The test score breakdowns by spending brackets (per student) remain unchanged when rounded to nearest percent.
    * ![School Budget Brackets Raw - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_budget_df_before_raw.png)
    * ![School Budget Brackets Raw - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_budget_after_raw.png)
    * ![School Budget Brackets Rounded - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_budget_df_before.png)
    * ![School Budget Brackets Rounded - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_budget_df_after.png)

* **Scores by School Size** - The test score averages by school size brackets remain unchanged when rounded to nearest percent.
    * ![School Size Brackets Raw - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_size_df_before_raw.png)
    * ![School Size Brackets Raw - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_size_df_after_raw.png)
    * ![School Size Brackets Rounded - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_size_df_before.png)
    * ![School Size Brackets Rounded - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_size_df_after.png)

* **Scores by School Type** - The test score averages by school type (District vs Charter) remain unchanged when rounded to nearest perecent.
    * ![School Type Brackets Raw - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_type_df_before_raw.png)
    * ![School Type Brackets Raw - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_type_df_after_raw.png)
    * ![School Type Brackets Rounded - Before](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_type_df_before.png)
    * ![School Type Brackets Rounded - After](https://raw.githubusercontent.com/Dreski9000/school-district-analysis/main/Resources/pycityschools_df_screenshots/school_type_df_after.png)

### Summary
In summary, the omission of test scores for 9th graders from Thomas High School (due to data corruption) bears little to no impact on the overall school district analysis due to how close the 9th grade averages were to the other grades, and the size of the omitted data, when compared to the district as a whole.