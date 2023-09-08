# PowerBi-HR-Analysis-Dashboard
This is my Final Dashboard Presentation from the class Current Trends in Software Development. 
The report is about HR Analysis and presents insights on employee distribution by department, employment status, and job titles over time, using visualizations such as bar charts, donut charts, stacked column charts, line charts, cards, Slicer and pie charts.
What can we do with the report:
With this report, you can easily understand the composition of employees in different departments, analyze the trend of employee count over time, and gain insights into the distribution of job titles and employment statuses, helping HR departments make informed decisions and track key metrics efficiently.

![image](https://github.com/Sumit363/PowerBi-HR-Analysis-Dashboard/assets/103460051/84bf2627-db30-41ff-bbac-dec50bf43010)

Here are the procedure I have used to create the Power Bi report.


First of all, we need to open Power BI Desktop app and import the file to the app. Here I have used " https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction " HR Analytics Data.csv file.


I have used 6 cards here in the report. 
Cards are simple visual elements that display a single value or calculation, making it easy to highlight important figures in a dashboard. 

Here after creating 6 cards from the visualization panel, I simply dragged and dropped the respective data name from the data panel.

1. Employee Count Card:
This card displays the total number of employees in the organization.

2. Average Age Card:
This card shows the average age of employees. 

3. Average Salary Card:
The average salary card displays the average salary of employees in the organization. 

4. Highest Salary Card:
This card shows the highest salary among all employees.

5. Lowest Salary Card:
Similarly, the lowest salary card presents the lowest salary among all employees, indicating the minimum salary paid in the organization.

6. Total Salary Cost Card:
The total salary cost card shows the sum of all salaries in the organization. It gives stakeholders an overview of the overall salary expenses incurred by the company.

I have also used 2 Slicer in the report. 

Department Slicer:
It lets users choose a specific department from the slicer, and once selected, all the visualizations in the report will update to show data related only to the chosen department.

To create the Department slicer in Power BI, follow these steps:

•	In the "Visualizations" pane on the right, click on the "Slicer" icon (looks like a filter).
•	Drag the "Department" field from your dataset into the "Values" section of the slicer.
•	The slicer will automatically generate a list of all departments available in the dataset.
Business Travel Slicer:
The Business Travel slicer allows users to filter employees based on their business travel frequency (e.g., Non-Travel, Travel Rarely, Travel Frequently.

•	In the "Visualizations" pane, click on the "Slicer" icon (filter icon).
•	Drag the "Business Travel" field from your dataset into the "Values" section of the slicer.
•	The slicer will automatically generate options for different business travel categories based on the data in the dataset.

Stacked Bar Chart:
A bar chart is used to show the count of employees in each department. 

To create this visualization:

•	Go to "Visualizations" pane on the right side.
•	Click on the "Bar chart" icon (looks like stacked bars).
•	Drag the "Department" field to the "Axis" section.
•	Drag the "Employee ID" field to the "Values" section.
•	Power BI will automatically count the number of employees per department and show it as bars on the chart.

![image](https://github.com/Sumit363/PowerBi-HR-Analysis-Dashboard/assets/103460051/f8e9a510-0622-4531-b685-81d7078ac416)

 

Donut Chart:
The donut chart is used to show the percentage of employees based on their employment status (e.g., Full-Time, Part-Time, etcTo create this visualization:

•	Go to the “Visualizations" pane.
•	Click on the "Donut chart" icon.
•	Drag the "Employment Status" field to the "Legend" section.
•	Drag the "Employee ID" field to the "Values" section.
•	Power BI will calculate the percentage of employees in each employment status and display it as a donut chart.

Stacked Column Chart:
This chart displays the count of employees by department and further divides it based on their gender. It's like the bar chart, but each bar is divided into segments representing different genders for each department.

To create this visualization:

•	Go to the “Visualizations" pane.
•	Click on the "Stacked column chart" icon (looks like stacked columns).
•	Drag the "Department" field to the "Axis" section.
•	Drag the "Employee ID" field to the "Values" section.
•	Drag the "Gender" field to the "Legend" section.
•	Power BI will automatically group employees by department and gender and show them as stacked columns in the chart.

Line Chart:
The line chart displays the trend of employee count over time. It shows how the number of employees has changed over a specific period (e.g., months or years). 
To create this visualization:

•	Go to the “Visualizations" pane.
•	Click on the "Line chart" icon (looks like a line graph).
•	Drag the "Date" field to the "Axis" section.
•	Drag the "Employee ID" field to the "Values" section.
•	Power BI will create a line chart showing the employee count over time based on the dates provided.

Pie Chart:
The pie chart shows the percentage of employees in each job title category. It's a circle divided into sectors, with each sector representing a job title category and its size indicating the proportion of employees in that category. 

To create this visualization:

•	Go to the “Visualizations" pane.
•	Click on the "Pie chart" icon (looks like a circle).
•	Drag the "Job Title" field to the "Legend" section.
•	Drag the "Employee ID" field to the "Values" section.
•	Power BI will calculate the percentage of employees in each job title category and display it as a pie chart.

Clustered Column Chart:
The clustered column chart is used to display a side-by-side comparison of data across different categories. 

To create the Clustered Column Chart:

•	In the "Visualizations" pane on the right, click on the "Clustered column chart" icon (looks like multiple vertical bars).
•	Drag the "Job Level" field to the "Axis" section.
•	Drag the "Total Emp" field to the "Values" section.


Matrix Visualization:
The matrix visualization in Power BI is a tabular representation of data that allows users to summarize and cross-tabulate information

To create the Matrix visualization:

•	In the "Visualizations" pane on the right, click on the "Matrix" icon (looks like a table with headers).
•	Drag “JobRole” to the Rows. 
•	Drag “Total Emp”, “Average of MonthlyIncome”, and “Average of PerformanceRating” to the Values section .


THANK YOU!!




