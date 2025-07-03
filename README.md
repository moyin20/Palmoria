# Palmoria
## Palmoria Group HR Analysis
The Palmoria group is a manufacturing company faced with the issue of gender inequality in its 3 regions and requires insights from the HR data to make notable decision regarding the issue which could affect the company tremendously.
My role is to analyze the HR data, figure out the gender inequality in each region and provide suitable recommendation for the management.

# EDA 
## Data Cleaning
Records of employees that no longer work for the company were removed from the salary columns as “null”, also departments that are not functioning were also removed as “null”.
We were assigned to give generic names to employees whose gender were undisclosed hence they were replaced with “Undisclosed”.
Blank rows were removed from the salary column as they belong to past employees and to ensure accurate column quality in the palmoria employee data.
While the Bonus Rules data was imported and unpivoted to be able to allocate bonus to each employee.

## Custom Columns
Custom columns were calculated to generate the Annual Bonus, and Bonus inclusive salary for the employees while conditional columns was created to create a salary band and to ensure that the company follows the rules of paying #90,000 as the minimum salary. Then the Palmoria employee data and the bonus rules data were merged to have a complete dataset.
Table was created to keep all the measures calculated in an organized format.

## Create Dashboard In PowerBI
 * Pie Chart
* Bar Chart
* Column Chart
* Clustered Bar Chart
* Clustered Column Chart
* Card
## Dashboard
* https://github.com/moyin20/Palmoria/blob/main/Palmoria%20Dashboard.png "See a screenshot of the dashboard in png.
*  
