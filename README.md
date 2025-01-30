# Project: HR Dashboard Analytics

This project is an HR dashboard designed to analyze employee data and provide insights into various aspects of the workforce.

## Project Overview

*   **Purpose:** This project aims to create a comprehensive HR dashboard to analyze employee data, identify key trends, and provide insights into factors such as attrition, employee demographics, satisfaction, and performance. The objective is to empower HR professionals with data-driven insights for better decision-making.

## Data Source(s)

*   The data for this project is from an employee dataset containing the following columns:
    *   `EmpID`: Employee ID
    *   `Age`: Age of the employee
    *   `AgeGroup`: Age group of the employee
    *   `Attrition`: Whether the employee has left the company (binary value, yes or no).
     *  `BusinessTravel`: How frequent the employee has been doing business travel
    *   `DailyRate`: Daily rate of the employee
    *   `Department`: Department of the employee
    *   `DistanceFromHome`: Distance from home for the employee
    *   `Education`: Level of education of the employee
    *  `EducationField`: Field of education of the employee
    *   `EmployeeCount`: Total employee count, it contains only one value and doesnt impact analysis.
    *   `EmployeeNumber`: Employee number.
    *   `EnvironmentSatisfaction`: Satisfaction level of the employee with the environment.
    *   `Gender`: Gender of the employee.
    *   `HourlyRate`: Hourly rate of the employee
    *   `JobInvolvement`: Job involvement level of the employee.
    *   `JobLevel`: Job level of the employee.
    *   `JobRole`: Job role of the employee.
    *   `JobSatisfaction`: Job satisfaction level of the employee.
    *   `MaritalStatus`: Marital status of the employee.
    *   `MonthlyIncome`: Monthly income of the employee.
        * `SalarySlab`: Salary slab of the employee.
    *  `MonthlyRate`: Monthly rate of the employee
    *   `NumCompaniesWorked`: Number of companies the employee has worked at.
    *  `Over18`: Whether the employee is over 18 or not.
    *   `OverTime`: Whether the employee is doing overtime or not.
    *  `PercentSalaryHike`: Percentage of salary hike given to the employee.
    *   `PerformanceRating`: Performance rating of the employee.
    *   `RelationshipSatisfaction`: Satisfaction level of the employee with relations.
    *   `StandardHours`: Standard hours of work for the employee.
    *  `StockOptionLevel`: Stock option level of the employee.
    *   `TotalWorkingYears`: Total working years of the employee.
    *   `TrainingTimesLastYear`: Training times of the employee last year.
    *  `WorkLifeBalance`: Work life balance of the employee
    *   `YearsAtCompany`: Years the employee has been at the company.
    *   `YearsInCurrentRole`: Years in the current role of the employee.
    *   `YearsSinceLastPromotion`: Years since the employee's last promotion.
    *   `YearsWithCurrManager`: Years the employee has been with the current manager.
    The dataset is located in the `HR_ANALYTICS.csv` file.

## Key Metrics & KPIs

The dashboard visualizes the following key metrics and KPIs:

*   Count of Employees
*   Attrition Count
*   Attrition Rate
*   Average Age
*   Average Salary
*   Average Years at Company

## Visualizations

The dashboard utilizes the following visualizations:

*   **Slicer:** Used for selecting and filtering by `Department`.
*   **Card Visuals:** Display key metrics such as count of employees, attrition count, attrition rate, average age, average salary, and average years at the company.
*   **Donut Chart:** Used to visualize attrition by education level.
*   **Bar Chart:** Used to visualize attrition by age group.
*  **Table:** Used to display different job roles.
*  **Tree Map:** Used to visualize the male-to-female ratio.
*   **Column Charts:** Used to visualize attrition by job role and attrition by salary slab.
*   **Area Chart:** Used to show attrition trends by years at the company.

## Key Features

*   **Interactive Filtering:** Users can filter the data by department using slicers.
*   **Insightful Visualizations:** Charts and graphs are designed to highlight key insights and trends within the employee data.

## Setup Instructions

The dashboard is built in Power BI, please open the file using Power BI desktop.

## Key Learnings

* Through this project, I gained a strong understanding of how to analyze and visualize HR data to address key business challenges. I learned to calculate relevant HR metrics like attrition rate and average salary and how to present these metrics in a format that is easy to understand by the business users. Also I learned the use of various Power BI visuals to provide interactive and insightful information related to employee data which can help HR professionals make data driven decisions.

## Usage

*   This dashboard is intended to be used by HR professionals and management to gain a better understanding of the workforce, make data-driven decisions related to employee retention, and identify areas for improvement.
