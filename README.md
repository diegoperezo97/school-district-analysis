# MODULE 4: PyCitySchools with Pandas

I'll learn about Jupyter notebooks and the fundamentals of Pandas in this subject. A Python package for data analysis and manipulation is called Pandas. To extract raw data from a CSV file, clean and analyze the data, combine data sets, conduct computations, and build tables, I'll use Pandas and the Jupyter notebook.

Each of these activities is a step in the data wrangling or data munching process that data analysts use to clean, sort, and transform data into a format that can be more readily evaluated and used to convey information. By organizing the data by data type, formatting the rows and columns, and sorting or grouping the data, I may wish to modify the way my data is organized or add structure throughout the data wrangling process. I might also need to choose whether to preserve or discard missing values and decide how to deal with values that don't match. I may need to decide whether to concatenate or combine several data sets with the same raw structure into a single, sizable dataset.

Pandas provides many sophisticated functions beyond Excel or VBA and is incredibly versatile and performance-optimized.

Let's examine the pandas library and Jupiter notebooks in more detail.

## Overview of the Analysis
In this module, I will be working with Maria, the chief data scientist for a city school district who is responsible for analyzing information from a variety of sources, and in a variety of formats. She was tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns. These insights will then be used to inform discussions and strategic decisions at the school and district level.

I will be helping Maria to analyze data on student funding, students’ standardized test scores (math and reading), as well as various information on the schools they attend. 

### Purpose
* Aggregate data and showcase trends in school performance to assist school board and superintendent in making decisions regarding the school budgets and priorities.

## Results of the Analysis
1. How is the district summary affected? 

**Table 2.1. District Summary Percentage Change**
| SUBJECT | BEFORE | AFTER | PERCENTAGE CHANGE
| ----------- | ----------- | ----------- | -----------
| Average Math Score | 0.984375 | 0.28125 | -71%
| Average Reading Score | 1.078125 | 0.359375 | -67%
| % Passing Math | 1.078125 | 0.359375 | -67%
| % Passing Reading | 1.078125 | 0.359375 | -67%
| % Overall Passing | 1.078125 | 0.359375 | -67%

2. How is the school summary affected? 

**Table 2.2. School Summary Percentage Change**
| SUBJECT | BEFORE | AFTER | PERCENTAGE CHANGE
| ----------- | ----------- | ----------- | -----------
| Average Math Score | 83.418349 | 83.350937 | -0.08%
| Average Reading Score | 83.84893 | 83.896082 | 0.06%
| % Passing Math | 93.272171 | 93.18569 | -0.09%
| % Passing Reading | 97.308869 | 97.018739 | -0.30%
| % Overall Passing | 90.948012 | 90.630324 | -0.35%

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 

**Table 2.3.a. Thomas High School Math and Reading Scores Change in Relation to Cabrera High School**
| SUBJECT | BEFORE | AFTER | PERCENTAGE CHANGE
| ----------- | ----------- | ----------- | -----------
| Average Math Score | 83.061895 | -0.43% | -0.35%| 0.08%
| Average Reading Score | 83.975780 | 0.15% | 0.09% | 0.06%
| % Passing Math | 94.133477 | 0.92% | 1.02% | -0.09%
| % Passing Reading | 97.039828 | -0.28% | 0.02% | 0.25%
| % Overall Passing | 91.334769 | 0.43% | 0.78% | -0.35%

**Table 2.3.b. Thomas High School Math and Reading Scores Change in Relation to Griffin High School**
| SUBJECT | BEFORE | AFTER | PERCENTAGE CHANGE
| ----------- | ----------- | ----------- | -----------
| Average Math Score | 83.351499 | 0.08% | 0.00% | 0.08%
| Average Reading Score | 83.816757 | 0.04% | 0.09% | -0.06%
| % Passing Math | 93.392371 | -0.13% | -0.22% | -0.09%
| % Passing Reading | 97.138965 | 0.17% | -0.12% | 0.05%
| % Overall Passing | 90.599455 | 0.38% | 0.03% | 0.35%

4. How does replacing the ninth-grade scores affect the following: 
  4a. Math and reading scores by grade:
  
The only affected school is 9th grade observations for Thomas High School. Therefore, no data is altered for any school nor grades, except for 9th grade observations for Thomas High School, having a NaN in our summary in this case.

  4b. Scores by school spending:
  
Given the significant numbers we are working with, there are no significant changes in any case except for “% Passing Reading”, where the change is sufficient to help round our numbers to the previous integer number.

  4c. Scores by school size:

Given the significant numbers we are working with, there are no significant changes in any case except for “% Passing Reading”, where the change is sufficient to help round our numbers to the previous integer number.
  
  4d. Scores by school type

Given the significant numbers we are working with, there are no significant changes in any case except for “% Passing Reading”, where the change is sufficient to help round our numbers to the previous integer number.


**Table 2.1 Response Time in Seconds Original vs. Refactored Code**
| YEAR | ORIGINAL | REFACTORED | % CHANGE | AVERAGE % CHANGE
| ----------- | ----------- | ----------- | ----------- | -----------
| 2017 | 0.984375 | 0.28125 | -71% | -69%
| 2018 | 1.078125 | 0.359375 | -67% | -69%

## Summary of the Analysis
Four changes to the school district analysis after reading and math scores have been replaced:
1. District summary
2. School summary
3. Grade difference between Cabrera and Griffin High Schools
4. Percentage of passing for reading tests for all four sub analyses: 

  4a. Math and reading scores by grade 
  
  4b. Scores by school spending 
  
  4c. Scores by school size 
  
  4d. Scores by school type
