# Predicting-Data-Science-Salaries
The dataset being utilized in this project is a dataframe of results from a survey that was given to workers in the Data Science Field, across the world. There were 3755 respondants and their answers were analyzed through the exploratory phase of the project.

In this project, the primary objective of the assignment was to create a machine learning model, either Regression (Supervised), Classification (Supervised), Clustering (Unsupervised), or Reinforcement Learning (Unsupervised). We opted to go down the regression model route, but wanted to fully explore it's capabilities. Thus, we fed our dataset into different types of regression models to see which one fit our data the best.

Prior to creating the models, we created feature transformation pipelines for our numerical and categorical data, to better aid the models in their predictions. 

The attributes in our dataset included:
'work_year', 'experience_level', 'employment_type', 'job_title','salary', 'salary_currency', 'salary_in_usd', 'employee_residence','remote_ratio', 'company_location', 'company_size'

---

Summary of Data Cleaning:

1. Dataset has no missing values.
2. There are 1171 duplicate rows,dropped duplicate rows.
3. Renaming the values in columns experience_level,company_size,employment_type,remote_ratio for better understanding.
4. remote_ratio changed to obj dtype after renaming the column.

---

Findings from Exploratory Analysis:

1. The plot shows that highest salary by Data Science tech lead is > 400,000 USD and the lowest by Power BI developer is < 30000 USD.
2. The average salary of workers in the Data Science field is between 100,000-150,000 USD.
3. For Employee Residence and Company location, the US is the highest in terms of frequency, followed by UK. A total of over 1900 Employees and Companies are resident in the US while other locations record values below 50 for both Employee residence and company location.
4. Top Data Science job titles include 'Data Engineer', ' Data Scientist', 'Data Analyst', and 'Machine Learning Engineer'
5. 'Israel', 'Puerto Rico', and 'United States' are the top 3 countries with the highest average salaries in the data science field.

---

Regression Models:

Prior to creating the models, we created feature transformation pipelines for our numerical and categorical data, to better aid the models in their predictions. 

More TBA.

   





