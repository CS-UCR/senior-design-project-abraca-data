
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5819074&assignment_repo_type=AssignmentRepo)
# CS178A-B-Template

## Table of Contents
- [Overview](#overview)
- [Team](#team)
- [Usage](#usage)
- [How To Run](#how-to-run)
- [Diagrams](#diagrams)
- [Dependencies](#dependencies)

## Overview
Riverside County has a low retention rate in their Department of Public Social Services whether an employee is leaving for another job or transferring between different divisions within the same department. This causes employee instability in the workplace and diminishes the available resources and time since the positions take time to fill and new employees require training. The goal of this project is to find what causes the low retention rate by looking at provided data and looking and demographics such as salary, age, education, etc. We will also be using ML model to analyze the features and find any correlations between the features.

## Team

<a href="https://github.com/Smitmodi71" target="_blank">Smit Modi </a>

<a href="https://github.com/tzaw0" target="_blank">Thet Zhaw </a>

<a href="https://github.com/jortega2" target="_blank">Juvenal Ortega </a>

<a href="https://github.com/jyjeachae" target="_blank">John Chae </a>



## Usage
Demo: <Link to youtube video>

<Screenshot of application>

## How To Run
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

### Mockups
Regression Analysis
**![](https://lh4.googleusercontent.com/YOxb5XewjtgCc3LCssw4ZLGLIl9zRsBBuo_VvgE7hiF6DzkNPfyMQzYgW7X5lOwbo7VoL6XLPagHNV_-YD-Kmz2queCyVJetLoPXaEiHzh8Ftvnj-L0S8flzrYkSWpDjy_49Dw6E)**
**![](https://lh6.googleusercontent.com/vidG5gqD2yb5_8ss6WDcMRAExy1XhZ3PQwc7hsq-1bPZv7dLq36DLl_Wpd2SSWKErxssoh-uk_-ekySGIFLrC6MxAh01McdmKvTCdMu2vdOTGQgtLkDp-zj7Lw8fYB4ueOBeyttp)**
**![](https://lh3.googleusercontent.com/W7FFSM_XUwy_cJ_LENuQVddEvn37b1UlttsXqaJZsGZ60wIA9bWTd43sjm6XEjdZjlhf04JQ05TFD89XrII2_w3iY8NJJJxvrAnOAaKE5YIP56H98sbdD7uIx2iRPPijxp6N46cs)**

  
PowerBI dashboard 

**![](https://lh4.googleusercontent.com/mEES8qNvE9ASe0_d9s3fCh4a1wXIvrPE06wtwMj62A9MV2p5Pva2F8HeyjYHqlr6Wp6sEVMaYnAfSmBZA3p1e2AgknLgCPnyZpy7VDZAqczyc1ZJyg1PJKS9z2BezrQP03aLRdGt)**
  
ML mockup with Linear Regression
  
**![](https://lh4.googleusercontent.com/FkyfsIdNo1Fv37i3KNtnD5AbHieQ69Q_0RNPH8fVFwixZS92JeE1uoAnQDk3P6OIU5A6uTWOvbL0IwqKX-2bm4wpkAQdPuvW3qdgEXtZC6GFXcSs3rXfXuruxm6M53DSfRtAOKAG)**


## Dependencies
Install Node Package Manager (npm). [Helpful Documentation](https://www.npmjs.com/get-npm)

