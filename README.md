# Google Advanced Data Analytics Capstone - A predictive model to identify at-risk employees using HR Data 📊 
Welcome to my Capstone Project for the Google Advanced Data Analytics Certificate offered through Coursera. As a culminating task, this project served as an encapsulation of all the skills and concepts taught throughout the course, all consolidated into one project, with the aim of applying those skills in a real-world scenario.

## The premise 💡
So here's the situation: we, as a data professional, have been approached by a fictitious company named Salifort Motors, and asked to help their HR department, who wants to improve employee satisfaction levels. To this end, you decide to build a classifier that aims to predict whether or not an employee is likely to leave the company. The idea behind this is twofold; in doing so, HR may be able to identify the factors that influence an employee to stay/leave. They will also save valuable time, resources and money that was used to recruit, hire, and onboard these employees by getting them to stay.

## Dataset obtention \& cleaning 📂
HR has provided us with an employee dataset consisting of 15000 rows of data. I made use of the Pandas library to import, observe, and clean the dataset. This included renaming columns to maintain consistency and ease-of-understanding, checking for missing values, and checking for and removing duplicate entries, as well as values that were considered outliers. This process ensures that the dataset is free of any data that could potentially negatively affect our analysis and distort the results.

## Exploratory Data Analysis 🔍
After the dataset was cleaned up, I conducted Exploratory Data Analysis, to get a feel for the data and get a sense of what I was working with. During stage, I was mainly concerned with uncovering the distribution of certain variables across several categories. This could be an important indicator of potential relationships among variables. For example, the following plot shows that there were significantly more work accidents in the Sales department than any other department within the company. 
![workplace_accidents](department_work_accidents.png)
