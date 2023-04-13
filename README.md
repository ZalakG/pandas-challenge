pandas-challenge

# Module-4_Challenge
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Background
----------

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

To start the Analysis first I created a repository named "pandas-challenge". I cloned the repo to my local machine. Inside my local Git repo, I created a folder named "PyCitySchool", an "Images" folder which has one image, and a README.md text file(added when created Git repo) which contains a written report of all the analysis and conclusion. 

In PyCitySchool folder:
-----------------------
1) Jupyter notebook called PyCity_School.ipynb to visualize data outcomes in table format which is the main script to run the analysis.
2) A Resources folder contains raw data of two csv files, schools_complete.csv and student_complete.csv 
3) A .ipynb_checkpoints folder

Process for Analysis:
---------------------
- I have used Jupyter notebook for visulizing data in table formate
- Imported Pandas library and used Python to analyze District Data of schools and showcase trends in school performances based of key metrics.
- Read raw data from csv files
- Merged the data of two csv files(schools_complete.csv and student_complete.csv) into complete_school to create new DataFrames to gather more information
- Performed all the calculation for key metrics i.e. District Summary, School Summary, Highest performaing schools, Lowest performing schools, Math score by grades, Reading      	scores by grades, Overall scores by grades, Scores by school spenending money for each students, Score by shcool size(Small , Medium, or Large), and Scores by school 	type(District or Charter)
- Visualized data with tables to tell the story and showcase the trends.
Note:
Detailed description of the code logic is in Juptor notebook in comments

Conclusions:
------------
- After calculating stastical analysis for Score by School Type, the Charter type schools have higher passingrate  in Reading and Math than the District type schools. Even if we consider Overall passing rate, Charter schools have very high passing rate than District schools so this will lead to the conclusion that top five performing schools are all cahrter schools and bottom five performing schools are District schools.

- After comparing Schools by size, We can see that all Large schools are District type Schools and all Medium or Small shools are Charter type schools and if we look at the math, reading and overall passing rate by scholl size than Large schools have very low passing rate compared to Small and Medium size schools.

- If we look at the Scores by school spending, There is no drastic diffrence in budget per student for both Charter and District Schools but still the Charter schools have lower passing rate in Math, Reading and Overall than District scholls. Even there is no corelation has seen between school spending and avg Math or Reading scores.

- Looking at the analysis for comparing Math and Reaidng scores, we can see that in general, students have lower Math scores compared to their readig scores.

