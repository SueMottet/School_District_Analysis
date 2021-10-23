# School District Analysis Overview

## Replacing one school's ninth grade reading and math scores

## Repeating the school district analysis

## School District Analysis written report
School data in a school district testing file shows evidence of academic dishonesty; specifically, reading and math grades for ninth graders at a single school appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. The request has come through to replace the math and reading scores for one grade at a single High School with NaNs while keeping the rest of the data intact. Once the data is replaced for those math and reading scores, a repeat of the school district analysis will be performed and a report will be created to describe how these changes affected the overall analysis.

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

* School Summary
* Top 5 5 performing schools, based on the overall passing rate
* Bottom 5 performing schools, based on the overall passing rate
* Average math score for each grade level from each school
* Average reading score for each grad level from each school
* Scores by school spending per student
* Scores by school size
* Score by school type

## School District Analysis changes - impact of replacing a school grade's math and reading scores with NaN
1.
2.
3.
4.
5.
