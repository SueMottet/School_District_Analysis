# School District Analysis Overview
After working with the chief data scientist for a city school district to perform analysis and provide aggregates of data used to identify trends in school performance for assisting their school board and superintendent in making decision around school budgets and priorities, it is discovered that school data in a school district testing file shows evidence of academic dishonesty specifically, reading and math grades for ninth graders at a single school appear to have been altered. 

Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The request has come through to replace the math and reading scores for one grade at a single High School with NaNs while keeping the rest of the data intact. Once the data is replaced for those math and reading scores, a repeat of the school district analysis will be performed and a report will be created to describe how these changes affected the overall analysis.

## Project background
The initial analysis work performed anaysis and aggregations on student funding and student's standard test scores to provide insights about performance trends and patterns. 
These insights are to be used to inform discussions and strategic decisions at the school and district level. 

Both sets of analysis include the following metrics:
* The district summary
* The school summary
* The top 5 and bottom 5 performing schools, based on the overall passing rate
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student, by school size, and by school type

##Project Goals:

### 1. Replacing one school's ninth grade reading and math scores

Before performing the replacement of the Thomas High School ninth grade reading and math scores the school data was populated with numbers like all the rest of the schools testing scores.

A de-identified sampling of the Thomas ninth grade data before the data replacement work is performed is shown here:
![Pre Replacement image](/Resources/did_pre_NAN_replacement.png)

After performing the replacement of the Thomas High School ninth grade reading and math scores with NaN, the school data was altered only for one school: Thomas High School and one grade: ninth grade. the rest of the school data was left as it was. 

A de-identified sampling of the school data showing the Thomas High School ninth grade data changed is shown here:
![After Replacement image](/Resources/did_after_NAN_replacement.png)

### 2. Repeating the school district analysis

## 3. School District Analysis written report


## Project Resources
* Jupyter Notebook
* Anaconda
* Pandas
* Python

## References
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
# School District Analysis Results

## School District Metrics
### District Summary Comparison

#### Before

![pre NaN District Summary image](/Resources/pre_district_summary.png)

#### After

![after NaN District Summary image](/Resources/after_NAN_district_summary.png)

## School Summary

#### Before

![pre NaN School Summary image](/Resources/pre_NAN_school_summary.png) 

* #### After

![after NaN School Summary image](/Resources/after_NAN_school_summary.png)

## Top 5 Performing Schools Comparision (based on the overall passing rate)

#### Before 

![pre NaN High Performing Schools image](/Resources/pre_NAN_high_performing_schools.png) 

#### After

![after NaN High Performing Schools Image](/Resources/after_NAN_high_performing_schools.png) 

## Bottom 5 Performing Schools Comparision (based on the overall passing rate)

#### Before 

![pre NaN Low Performing Schools image](/Resources/pre_NAN_low_performing_schools.png) 

#### After

![after NaN Low Performing Schools image](/Resources/after_NAN_low_performing_schools.png) 

## Average math score for each grade level from each school

#### Before 

![pre NaN Averge Math Scores image](/Resources/pre_NAN_math_scores_by_grade.png) 

#### After

![after NaN Low Performing Schools image](/Resources/after_NAN_math_scores_by_grade.png) 


## Average reading score for each grade level from each school

#### Before 

![pre NaN Averge Reading Scores image](/Resources/pre_NAN_reading_scores_by_grade.png) 

#### After

![after NaN Averge Reading Scores image](/Resources/after_NAN_reading_scores_by_grade.png) 

## Scores by school spending per student

#### Before 

![pre NaN Scores By Spending image](/Resources/pre_NAN_scores_by_spending.png) 

#### After

![after NaN Scores By Spending image](/Resources/after_NAN_scores_by_spending.png) 

## Scores by school size

#### Before 

![pre NaN Scores By School Size image](/Resources/pre_NAN_scores_by_school_size.png) 

#### After

![after NaN Scores By School Size image](/Resources/after_NAN_scores_by_school_size.png) 

## Score by school type

#### Before 

![pre NaN Scores By School Type image](/Resources/pre_NAN_scores_by_school_type.png) 

#### After

![after NaN Scores By School Type image](/Resources/after_NAN_scores_by_school_type.png) 

## School District Analysis changes - impact of replacing a school grade's math and reading scores with NaN
1.
2.
3.
4.
5.
