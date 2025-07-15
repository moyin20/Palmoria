# Palmoria
## Palmoria Group HR Analysis
The Palmoria group is a manufacturing company faced with the issue of gender inequality in its 3 regions and requires insights from the HR data to make notable decision regarding the issue which could affect the company tremendously.
My role is to analyze the HR data, figure out the gender inequality in each region and provide suitable recommendation for the management.

# EDA 
Records of employees that no longer work for the company were removed from the salary columns as “null”, also departments that are not functioning were also removed as “null”.
We were assigned to give generic names to employees whose gender were undisclosed hence they were replaced with “Undisclosed”.
Blank rows were removed from the salary column as they belong to past employees and to ensure accurate column quality in the palmoria employee data.
While the Bonus Rules data was imported and unpivoted to be able to allocate bonus to each employee.
The Gender Distribution by Region between the Male and Female differ by a margin of 2.53% across the 3 regions while the ratings count by gender proved the rating counts of the make gender higher than any other gender.
The total amount to be 70 Million Naira.
However, Palmoria Group has failed to meet the requirement of paying their staff a minimum of 90,000 as there are still some employee being paid below 90,000

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
* [ Download the file](https://github.com/moyin20/Palmoria/blob/main/Assignment.pbix) and open in PowerBI Desktop for interactive viewing.
* [See a picture of the dashboard](https://github.com/moyin20/Palmoria/blob/main/Palmoria%20Dashboard%202.png) and 
