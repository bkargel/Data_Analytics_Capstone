# Data_Analytics_Capstone - Model for Predicting Worker Compensation Highest Claims Process

This repository was created in order to house the work related to my Data Analytics capstone project, a project that explores patterns of workplace injuries using age, claim type, and whether or not an employee is represented to estimate the highest level of claim activity and help employers understand likely claim outcomes.

The report can be found here: https://www.overleaf.com/read/cdwftsjxmtgp#eac724

This project contains three Jupyter notebooks - Clean_WC_Claims, Exploratory Analysis, and Predictive Modeling. Each notebook contains pieces of the project to

## Clean_WC_Claims
This notebook contains all of the cleaning process for the project. First, the data is filtered to only include accident dates between 2020-2022, then unneeded columns are removed, and new names are given to columns with names that are either awkard or too long. Next, categorical data is replaced with numerical data to make the data easier to process in predictive modeling. These columns include Part of Body, Highest Process, Represented, and Gender.Finally, the data is verified with row and column counts, and a preview of the first line of data.

## Exploratory Analysis
Exploratory Analysis contains all of the summary statitics, correlations, and visualizations for the project. 

## Predictive Modeling
This notebook houses all of the code for the various models that were run during the project. 

## References
1. Barkved, K.: How to know if your machine learning model has good performance,https://www.obviously.ai/post/machine-learning-model-performance#:~:text=Good%20accuracy%20in%20machine%20learning,also%20consistent%20with%20industry%20standards.
2. Fawcett, A.: Data science in 5 minutes: What is one hot encoding?, https://www.educative.io/blog/one-hot-encoding
3. New York State Department of Labor: Laws governing the employment of minors, https://dol.ny.gov/system/files/documents/2023/07/p882-12-22.pdf
4. State of New York Workers’ Compensation Board: Assembled workers’ compensation claims: Beginning 2000, https://catalog.data.gov/dataset/assembled-workers-compensation-claims-beginning-2000
5. Patil, V.: Importance of exploratory data analysis in the journeyof data science project (part i), https://medium.com/@vpatil12/importance-of-exploratory-data-analysis-in-the-journey-of-data-science\-project-part-i-fbe18bac479c
