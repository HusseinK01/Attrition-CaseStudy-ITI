
# ABC Corporation Employee Attrition Analysis Project

https://github.com/HusseinK01/Attrition-CaseStudy-ITI/assets/104552707/b21b14b2-3d38-4c91-82cc-8ea022d77cd6

## Project Overview:
ABC Corporation is a multinational company grappling with employee attrition challenges. In a bid to comprehend the underlying factors contributing to attrition and devise effective retention strategies, the company has embarked on a Power BI project to conduct a comprehensive analysis of their attrition data.

## Data Sources:
### Database:
The project utilizes three primary database tables:
1. **Employee_survey**: Contains responses from employees regarding their satisfaction levels, work-life balance, etc.
2. **Manager_survey**: Comprises responses from managers regarding employee performance and related aspects.
3. **EmployeeInfo**: Provides demographic information, job roles, etc.

### IN/OUT Times:
Additionally, data from the Clock-In-Machine for the year 2015 has been incorporated, consisting of two sheets encompassing in/out times for all employees.

## Methodology:
1. **Data Collection**: Data was gathered from multiple sources, including databases and CSV files.
2. **Data Preparation**: Various data preparation techniques such as reshaping, pivoting, aggregating, and filtering were employed to prepare the data for analysis.
3. **Data Model**: A dimensional model was constructed to integrate the diverse data sources and facilitate the subsequent reporting phase.
4. **Visualization and Dashboarding**: An interactive dashboard was developed using Power BI to effectively communicate insights derived from the analysis.

## Modeling:
### Facts:
1. **FactAttendance**: Records daily employee check-in and check-out times, work durations, overtime durations, early or late arrivals, and absenteeism status. 
   (disabled load for this fact table due to its large size increasing file size to above github limits.) 
2. **YearlyFact**: Captures yearly averages of employee work duration, overtime duration, early/late arrivals, absenteeism, and scores obtained from the annual surveys conducted within the company.

### Dimensions:
1. **Date Dimension**
2. **Employee Dimension**
3. **Survey Dimension**

