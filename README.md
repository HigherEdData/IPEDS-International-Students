# IPEDS-International-Students

### By Camellia Haghverdian

Abstract:

In this replication project, I am using IPEDS data to examine the relationships between the total of international students in American universities, total of Hispanic students, and nine different regions in the US. To choose my variables, I downloaded the dictionaries for two of the datasets that I merged together (dictionary links provided down below) and I looked at the dictionaries and highlighted the variables I was interested in, all of which I have included in my codes. For this project, I chose 3 main variables: my dependent variable is the total of international students (efnralt-continuous variable) and my independent variables are the total of Hispanic students (efhispt-continuous variable) and nine different regions across the US (obereg-categorical variable). My hypothesis is that by every increase in the percentage of total Hispanic students at a given region, there is an increase in the percentage of total international students in the US, and to do so, I run OLS regression and interaction model. I also created a bar chart to show the percent of internaitonal students in each of the 9 US regions.

File Organization:
In the home directory of this package, 8 files are important to look at for replication:

1. Data folder: includes c_data_download file that has the codes for downloading, unzipping, merging datasets, labeling, and generating variables.
2. Figures folder: contains a pdf for the bar chart.
3. Tables folder: contains variable definition and descriptive statistics.
4. f1_international_students_and_region.ipynb: contains the codes I ran to create a figure for the percent of international students in each of the nine US regions.
5. README.md (the file you are reading now): contains an abstract and explanation on the file organization
6. t1_variable_definitions: contains codes for creating a word document for the variable descriptions table.
7. t2_descriptive_statistics: contains codes for creating standard deviation and mean tables with an rtf file.
8. t3_regression_estimates: contains codes for running regression

**IPEDS Data Link**
- https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx?year=2012&sid=b58517b8-bfd1-4682-8d77-1ff902f85246&rtid=5

**Data Dictionaries**
- https://nces.ed.gov/ipeds/datacenter/data/HD2022_Dict.zip
- https://nces.ed.gov/ipeds/datacenter/data/EF2022A_Dict.zip

