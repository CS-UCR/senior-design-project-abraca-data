
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5819074&assignment_repo_type=AssignmentRepo)
# CS178A-B-Template

## Table of Contents
- [Overview](#overview)
- [Team](#team-members)
- [Usage](#usage)
- [How To Run](#how-to-run)
- [Diagrams](#diagrams)
- [Dependencies](#dependencies)

## Overview
Riverside County has a low retention rate in their Department of Public Social Services whether an employee is leaving for another job or transferring between different divisions within the same department. This causes employee instability in the workplace and diminishes the available resources and time since the positions take time to fill and new employees require training. The goal of this project is to find what causes the low retention rate by looking at provided data and looking and demographics such as salary, age, education, etc. We will also be using ML model to analyze the features and find any correlations between the features.

## Team Members

<a href="https://github.com/Smitmodi71" target="_blank">Smit Modi </a>

<a href="https://github.com/tzaw0" target="_blank">Thet Zaw </a>

<a href="https://github.com/jortega2" target="_blank">Juvenal Ortega </a>

<a href="https://github.com/jyjeachae" target="_blank">John Chae </a>



## Usage
Demo: Run the notebooks. kfold.ipynb and distance_calculation.ipynb are still work in progress. 

<Screenshot of application>

## Dataset to look for when running specific ML model: 
 - Use the dataset named source_2021-12-07-09-51-43.csv ( inside Machine Learning Models ) to run the ML models that starts with
 - (With/Without Feature Importance and Random Forest F1 score)
 -  <a href="https://github.com/CS-UCR/senior-design-project-abraca-data/blob/f7d150782cf711d45ec7caa5726289ebd5fac3f0/Machine%20Learning%20Models/source_2021-12-07-09-51-43.csv" target="_blank">source_2021-12-07-09-51-43.csv </a>
 
## How To Run
 You can use the attached PowerBI file and use the PowerBI application to view the dashboard. Data analysis and ML analysis are located in the .ipynb notebook files which you can look at our analysis or run the code yourself.
 
 In order to run the Notebooks, install [Jupyter Notebook](https://jupyter.org/install) and upload the notebooks.
 For any dependencies used in the notebook, view [Dependencies](#dependencies).
<!---
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
-->
## Diagrams

Due to the unique nature of our project, we do not have diagrams. Instead we outline our project with features and descriptions on how we plan to use the ML model; list of tools, methods, and algorithms we will use; and mockups of our end-product. 

### Features and Descriptions 

 -   Age - Visualize the age group of people in each department, and calculate the retention rate for this
    
-   Duration - Calculate the average number of days employees stayed in each department or left the job
    
-   Distance - Calculate how distance plays a role in an employee staying or quitting the job using Google Maps API
    
-   Hourly Pay/Department name - Find the average of how hourly pay has changed over the years in each department and then compare that with different counties. See if hourly pay has an effect on duration. For example comparing Riverside County vs Los Angeles County etc
    
-   Change Division - Calculate how many employees changed the division in recent years
    
-   Between Divisions - compare retention rate and salary between divisions

### List of Tools, Methods, and Algorithms
- Jupyter Notebook and Google Colab for data analysis in Python
- PowerBI for the dashboard as this is what Riverside County currently uses to visualize the data 
- Web scraping of websites to find salary and cost of living of similar job positions
- ML tools such as linear regression and KNN to analyze the dataset 
 
### EDA Analysis 
## Yearly Retention Rate:
- Shows it is declining since 2010 
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Yearly%20Retention%20Rate.PNG?raw=true)
 
## Retention Rate By Divisions:
- Children Services has the lowest retention rate followed by Self-Sufficency 
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Retention%20Rate%20by%20division.PNG?raw=true)
 
## Retention Rate By Sex:
- There’s no correlation between gender and retention rate as they trend together
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Retention%20Rate%20by%20sex.PNG?raw=true)
 
## Retention Rate By Classification:
- Staffs have lower retention rate compared to other groups
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Retention%20Rate%20by%20classification.PNG?raw=true)
 
## Retention Rate By Work Distance From Home:
- There is no correlation between distance from work and home and retention rate. 
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Distance.PNG?raw=true)
 
## Duration (Current vs. Past):
- Shows the duration of employment in the department
- Majority of employees (both past and current) has been employed for more than 5 years
- About 36% of the employees in our data were past employees who worked less than 5 years
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Duration%20current%20vs%20past.PNG?raw=true)
 
## Duration Between Divisions:
- The number of past employees who worked less than 5 years in Children Services is higher than average
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/duration%20between%20division.PNG?raw=true)
 
## Duration Between Ending Age Groups:
- This might be misleading as we are looking at ending age group
- Those who stay longer will moves up into higher age group so there’ll be less employees who had worked less than 5 years in those age groups
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/duration%20between%20ending%20age%20group.PNG?raw=true)

## Duration Between Staring Age Groups:
- There is less correlation when looking at the age group of when the employees were hired
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/duration%20age%20group.PNG?raw=true)
 
## Duration Between Classification:
- Staffs has more employees who worked less than 5 years compared to others
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/duration%20classification.PNG?raw=true)

## Comprate Distribution:
- The distribution of comprate for past employees who worked less than 5 years is more to the left
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/comprate%20distribution.PNG?raw=true)

### Machine Learning Models:
 
## XGBoost
- F1 scores: 71.39%, 70.97%, 76.50%, 78.09%, 80.82%, 50.58%
- Accuracy for each label:
- Retirement: 76.96%
- Termination: 88.82%
- Working: 51.85%
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/XGBoost.PNG?raw=true)
 
## Random Forest
- Accuracy for each label:
- Retirement: 70.96%
- Termination: 81.19%
- Working: 25.67%
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Random%20Forest%20machine.PNG?raw=true)
 
## Neural Network
- Features: Duration, Age_group, comprate, Division, Last_pay_raise 
- Labels and prediction accuracy
- Retirement (43.97%), Termination (77.32%), Working (55.18%)
- F1 Scores:19.36%, 67.82%, 76.5%, 78.33%, 79.11% and 64.22% average

 
### -----------------------------------------------------------------------------------------------------------------------------
### Everything below includes the MockUps and Draft versions we worked on early in the quarter to understand and clean the dataset. 
### -----------------------------------------------------------------------------------------------------------------------------
 
- Regression Analysis
**![](https://lh4.googleusercontent.com/YOxb5XewjtgCc3LCssw4ZLGLIl9zRsBBuo_VvgE7hiF6DzkNPfyMQzYgW7X5lOwbo7VoL6XLPagHNV_-YD-Kmz2queCyVJetLoPXaEiHzh8Ftvnj-L0S8flzrYkSWpDjy_49Dw6E)**
**![](https://lh6.googleusercontent.com/vidG5gqD2yb5_8ss6WDcMRAExy1XhZ3PQwc7hsq-1bPZv7dLq36DLl_Wpd2SSWKErxssoh-uk_-ekySGIFLrC6MxAh01McdmKvTCdMu2vdOTGQgtLkDp-zj7Lw8fYB4ueOBeyttp)**
**![](https://lh3.googleusercontent.com/W7FFSM_XUwy_cJ_LENuQVddEvn37b1UlttsXqaJZsGZ60wIA9bWTd43sjm6XEjdZjlhf04JQ05TFD89XrII2_w3iY8NJJJxvrAnOAaKE5YIP56H98sbdD7uIx2iRPPijxp6N46cs)**

  
PowerBI dashboard 

 **![](https://lh4.googleusercontent.com/mEES8qNvE9ASe0_d9s3fCh4a1wXIvrPE06wtwMj62A9MV2p5Pva2F8HeyjYHqlr6Wp6sEVMaYnAfSmBZA3p1e2AgknLgCPnyZpy7VDZAqczyc1ZJyg1PJKS9z2BezrQP03aLRdGt)**
  

### Early Drafts EDA
- This was done during last quarter when we were trying to understand and clean the data. 
 
Attrition Distribution ( Ex-employees vs Current employees )
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Attrition%20Distribution.PNG?raw=true)

Leavers by division
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Leavers%20by%20Job%20role.PNG?raw=true)
 
Leavers by Jobrole
![](https://github.com/CS-UCR/senior-design-project-abraca-data/blob/main/Project%20Screenshots/Leavers%20by%20division.PNG?raw=true)
 
## Dependencies
- Install pip [Helpful Documentation](https://pip.pypa.io/en/stable/installation/)
- Libraries to install using pip
  - pandas [Documentation](https://pandas.pydata.org/docs/)
  - numpy [Documentation](https://numpy.org/doc/)
  - plotly [Documentation](https://plotly.com/python/)
  - scikit-learn [Documentation](https://scikit-learn.org/stable/)
  - xgboost [Documentation](https://xgboost.readthedocs.io/en/stable/)
- Install googlemaps. [Helpful Documentation](https://pypi.org/project/googlemaps/)
