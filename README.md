# School District Analysis Overview
After working with the chief data scientist for a city school district to perform analysis and provide aggregates of data used to identify trends in school performance for assisting their school board and superintendent in making decision around school budgets and priorities, it is discovered that school data in a school district testing file shows evidence of academic dishonesty specifically, reading and math grades for ninth graders at a single school appear to have been altered. 

Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The request has come through to replace the math and reading scores for one grade at a single High School with NaNs while keeping the rest of the data intact. Once the data is replaced for those math and reading scores, a repeat of the school district analysis will be performed and a report will be created to describe how these changes affected the overall analysis.

## School District Analysis Background
The initial analysis work performed analysis and aggregations on student funding and student's standard test scores to provide insights about performance trends and patterns. 
These insights are to be used to inform discussions and strategic decisions at the school and district level. 

### School District Analysis Aggregates
Both sets of analysis include the following metrics:
* The district summary
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

## Key Project Deliverables:
### 1. Replacing one school's ninth grade reading and math scores

Before performing the replacement of the Thomas High School ninth grade reading and math scores, the school data was populated with numbers like testing scores for all the rest of the schools.

A de-identified sampling of the Thomas ninth grade data before the data replacement work is performed is shown here:
![Pre Replacement image](/Resources/did_pre_NAN_replacement.png)

After performing the replacement of the Thomas High School ninth grade reading and math scores with NaN, the school data was altered only for one school: Thomas High School and one grade: ninth grade. the rest of the school data was left as it was. 

A de-identified sampling of the school data showing the Thomas High School ninth grade data changed is shown here:
![After Replacement image](/Resources/did_after_NAN_replacement.png)

### 2. Repeating the school district analysis
After performing the replacement of the Thomas High School ninth grade reading and math scores with NaN, the analysis was repeated using the altered data and these metrics were recalculated:
* The district summary
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

### 3. School District Analysis written report comparing results
The written report on this school district analysis is included in this README.

### Project Resources
* Jupyter Notebook
* Anaconda
* Pandas
* Python

### References
* Anaconda installation documentation https://docs.anaconda.com/anaconda/install/
* Anaconda - creating a development environment https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands
* Anaconda  - activating a development environment https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment
* Anaconda - deactivating a development environment https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#deactivating-an-environment
* Anaconda - deleting a development environment https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#removing-an-environment
* Adding a development environment to Jupyter Notebook https://ipython.readthedocs.io/en/stable/install/kernel_install.html
* Localhost https://whatismyipaddress.com/localhost
* Computer port numbers https://www.expressvpn.com/what-is-my-ip/port-number
* Pandas Series https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.sample.html
* Pandas DataFrame https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.html
* Pandas - read_csv() function https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html
* Importing Python modules and packages https://www.pythonlikeyoumeanit.com/Module5_OddsAndEnds/Modules_and_Packages.html
* Pandas DataFrame head() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html
* Pandas DataFrame tail() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.tail.html
* Pandas isnull() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.isnull.html
* Pandas notnull() http://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.notnull.html
* Pandas dropna() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dropna.html
* Pandas fillna() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.fillna.html
* Pandas - working with missing data https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html
* Pandas - get the data types of a DataFrame https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dtypes.html
* Pandas - changing data types https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.astype.html
* Pandas - strip() https://docs.python.org/3/library/stdtypes.html#string-methods
* Pandas replace() https://docs.python.org/3/library/stdtypes.html#string-methods
* Pandas  - merging DataFrames https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.merge.html
* Pandas - merging, joining, and concatenating DataFrames https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html
* Pandas - unique() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.unique.html
* Pandas Format examples https://docs.python.org/3.4/library/string.html#format-examples
* Pandas Format specification https://docs.python.org/3.4/library/string.html#format-specification-mini-language
* Pandas set_index method https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.set_index.html
* Pandas value_counts() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.value_counts.html
* Pandas groupby() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html
* Pandas sort_value() https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sort_values.html
* Pandas cut() https://courses.bootcampspot.com/courses/811/pages/4-dot-11-dot-2-categorize-the-spending-bins?module_item_id=301219
*
# School District Analysis Results Summary
The school district analysis results include a number of metrics aimed at identifying trends in school performance.  Removing data for a whole grade at one of the schools in the district will impact the accuracy of the school performance information and make identifying these trends more difficult. The nature of these impacts will be detailed as part of this analysis results summary.

## School District Metrics
### District Summary Comparison
The district summary information changed after the replacement but only slightly and the data change would likely not be evident to data users (the school board and superintendent)

The District Summary before the Thomas ninth grade data replacement work is performed is shown here:
![pre NaN District Summary image](/Resources/pre_district_summary.png)

The District Summary after the Thomas ninth grade data replacement work is performed is shown here:
![after NaN District Summary image](/Resources/after_NAN_district_summary.png)

## School Summary
The school summary information changed after the replacement but only for Thomas High School and the data change would likely not be evident to data users (the school board and superintendent). It looks like removing the ninth grade testing scores made the Thomas High School math, reading, and overall testing numbers improve.

The School Summary before the Thomas ninth grade data replacement work is performed is shown here:
![pre NaN School Summary image](/Resources/pre_NAN_school_summary.png) 

The School Summary after the Thomas ninth grade data replacement work is performed is shown here:
![after NaN School Summary image](/Resources/after_NAN_school_summary.png)

## Top 5 Performing Schools Comparison (based on the overall passing rate)
The top five performing schools information changed after the replacement but only for Thomas High School and the data change would likely not be evident to data users (the school board and superintendent). It looks like removing the ninth grade testing scores did not impact Thomas High School's performance rank.

The top five performing schools before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN High Performing Schools image](/Resources/pre_NAN_high_performing_schools.png) 

The top five performing schools after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN High Performing Schools Image](/Resources/after_NAN_high_performing_schools.png) 

## Bottom 5 Performing Schools Comparison (based on the overall passing rate)
The bottom five performing school information did not change after the replacement. Thomas High School data did not factor into this data set either before or after the data replacement other than be part of an overall rank which did not change.

The bottom five performing schools before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Low Performing Schools image](/Resources/pre_NAN_low_performing_schools.png) 

The bottom five performing schools after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Low Performing Schools image](/Resources/after_NAN_low_performing_schools.png) 

## Average math scores for each grade level from each school
The average math scores for each grade changed after the data replacement work but only for Thomas High School.

The average math scores for each grade level before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Averge Math Scores image](/Resources/pre_NAN_math_scores_by_grade.png) 

The average math scores for each grade level after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Low Performing Schools image](/Resources/after_NAN_math_scores_by_grade.png) 


## Average reading scores for each grade level from each school
The average reading scores for each grade changed after the data replacement work but only for Thomas High School.

The average reading scores for each grade level before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Averge Reading Scores image](/Resources/pre_NAN_reading_scores_by_grade.png) 

The average reading scores for each grade level after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Averge Reading Scores image](/Resources/after_NAN_reading_scores_by_grade.png) 

## Scores by school spending per student
The scores by school spending information changed after the replacement because the percentages were impacted.

The scores by school spending before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Scores By Spending image](/Resources/pre_NAN_scores_by_spending.png) 

The scores by school spending afer the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Scores By Spending image](/Resources/after_NAN_scores_by_spending.png) 

## Scores by school size
The scores by school size information changed after the replacement because the percentages were impacted.

The scores by school size before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Scores By School Size image](/Resources/pre_NAN_scores_by_school_size.png) 

The scores by school size after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Scores By School Size image](/Resources/after_NAN_scores_by_school_size.png) 

## Score by school type
The scores by school type information changed after the replacement because the percentages were impacted.

The scores by school type before the Thomas ninth grade data replacement work is performed are shown here:
![pre NaN Scores By School Type image](/Resources/pre_NAN_scores_by_school_type.png) 

The scores by school type after the Thomas ninth grade data replacement work is performed are shown here:
![after NaN Scores By School Type image](/Resources/after_NAN_scores_by_school_type.png) 

## School District Analysis changes - impact of replacing a school grade's math and reading scores with NaN
1. As part of the presentation of this altered information, the presenter could inform data users of the special circumstances around the data changes and if needed notate this information on any handouts etc.
2. District Summary was impacted slightly
3. Thomas High School's testing scores in the School Summary were impacted by the data replacement work and may be misleading.
4. The data replacement did not have an effect on Thomas High School's overall ranking or the ranking of other schools.
5. Because the average math and reading score are by grade, the replacements show and it is evident that the Thomas High School ninth grade scores are not being calculated.
6. The scores by spending, school size, and school type are percentages and as such the results for all these were impacted by the data replacement.
