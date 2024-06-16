# US-Census data analysis 
## Table of contents
## Glossary
- Region: An area, especially part of a country or the world having definable characteristics but not always fixed boundaries.
- Census:  A periodic governmental count of a population that usually includes social and economic information.
- US: United States
- Census_division: A sub-category in the region of the country.
- States: The states making up America
- Measures: A measure in Power BI is a calculated value based on an aggregation or mathematical operation, while a column is a data field in a table.

## Project Overview
This Power BI report aims to display the total number of Americans from the year 2015 by state, region and census division via a map chart, bar chart and table respectively. Lastly, the report contains a ribbon chart which allows the end user to see the growth of the American population by state from 1950 to 2015. <br />
Additionally, another page contains a slider allowing a filter between the range of 1950 to 2015 to acquire population based on the period the user selects.


## Report
![Screenshot (481)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/54d6b641-4cc3-4c94-8767-ed5c7ced9289)

## Filter page table
![Screenshot (482)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/4c3f1663-1d26-4e1a-9404-8bacf8c77e24)


## Data Sources
Multiple CSV files namely:
- US-states-GDP-by-year.CSV
- Us-states-population-by-year.csv
- US-states.csv
## Dataset columns in the report
- Census region
- Census division
- States
- Abbreviations
- Sum of 2015 population

## Tools used
- Power BI: Microsoft Power BI is an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence. It is part of the Microsoft Power Platform.

## Data cleaning and transformation process
Measures were created to help aid in getting further analysis for the report like making a calculated field in tableau or a new column in Excel.

Furthermore, measures are created using the DAX programming language. The measures in the report include:
1. Begin population <br /> ![Screenshot (473)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/ca07abfa-f468-4a66-8dcb-6a6beaf759a8)
2. End population <br /> ![Screenshot (474)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/b6bf1463-1d2b-43af-a3f4-3c06fe6f7a3f)
3. Growth rate <br /> ![Screenshot (475)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/853bb355-e7a0-4efe-b58b-8097b3e15c0b)
4.  Population <br /> ![Screenshot (476)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/9dc3dcb0-b92f-4bd0-ae33-a05967b5b2d8)
5.  States measure <br /> ![Screenshot (477)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/36a9005f-557c-4951-883e-d2ea1b779ea0)
6.  Table title <br /> ![Screenshot (479)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/63485bb8-c99b-4734-80e9-7e017f73db1b)
7.  Tool tip title <br />![Screenshot (480)](https://github.com/Tyroneekhator/us-census-data/assets/72547969/bc78a18a-0faf-4fef-9563-906436251b73)
   




   


