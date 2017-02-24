# edX--MSDS-Curriculum--DAT207x
for DAT207x Analyzing and Visualizing Data with Power BI course on edX as part of the Microsoft Data Science curriculum

[DAT207x Analyzing and Visualizing Data with Power BI](https://courses.edx.org/courses/course-v1:Microsoft+DAT207x+1T2017/)

In this course, you will learn how to connect, explore, and visualize data with Power BI. Power BI Desktop provides a free-form canvas for drag-and-drop data exploration as well as an extensive library of interactive visualizations, simple report creation, and fast publishing to the Power BI service.

The Power BI product team will guide you through Power BI end-to-end, starting from how to connect to and import your data, author reports using Power BI Desktop, publish those reports to the Power BI service, create dashboards, and share to business users so that they can consume the dashboards through the web and their mobile devices.

The course is designed for self-paced study of around 2-4 hours per week for six weeks, including lectures, quizzes, labs and further readings. All quizzes and lab exercises are graded. The quizzes account for 30% of the total grade, the lab exercises accounts for 65% of the total grade, and the mandatory survey accounts for the remaining 5%. You must achieve an overall score of 70% to pass the course.

## Course Outline
### Module 1: Power BI Desktop Data Transformations
- Connecting to a Database
- Basic Data Transformations
- Managing Queries - creating Query Groups
- Splitting Data in one column to new columns
- Changing Data Types - dates, numbers, text
- Working with Dates - pulling out info from Dates (e.g. the day of the week, duration)
- Removing (redundant pieces or intermediate steps) and Reordering Columns
- Conditional Columns - new column based on the values in another one (if-then-else syntax)
- Connecting to Files (e.g. csv, xml files) in a Folder - parsing data, combining data with the other data - merging / appending, adding Custom Column with an expression to fill null values,     
- Merge Queries - merging data together (like doing a SQL's JOINT) into a single query
- Query Dependency View - understanding queries' references and connections, state of queries,
- Transforming Less Structured Data (e.g. pivoted Excel data) - using Transform Tab: transpose table, use first row as headers, fill down / up, unpivot; building simple visuals
- Enter Data - create table, pasting data from clipboard formats (e.g. excel tables)
- Query Parameters - specify a prompt to allow selecting a parameter to filter data pull for a report; saving as Power BI Desktop file; saving as Power BI template and sharing reports   

#### Lab 1: Merging Files and Transforming Data using Power BI Desktop
- Import Data from Access Database
- Import a Less Structured Data from an Excel File

----
### Module 2: Power BI Desktop Modelling
Data Modelling in Power BI Desktop
- Managing Data Relationships
- Creating Calculated Columns with a DAX expression
- Optimizing Models for Reporting - hiding unused fields in tables; Modeling - Sort by Column, Data Type, and Data Format
- Creating Calculated Measures - Create Measure with DAX (the Data Expression Language); Choose Home Table for a Measure;

>> DAX has lots of very useful functions, especially for defining things like time based calculations, Year to Date or Year Over Year calculations.
>>
>> YTD Revenue = TOTALYTD(SUM(Sales[Revenue]), 'Date'[Date])

- Creating and Managing Hierarchies
- Using Calculated Tables
- Time Intelligence
- Manually Typing in a Data Table
- Include / Exclude
- Grouping / Binning

#### Lab 2:
- Manage Table Relationships
  1. create a relationship between tables
  2. review the relationship (cardinality  / Cross filter direction)
- Create Last Year Comparison measures
  1. Total Sales - calculates the total sales
  2. LY Sales - calculates last year sales (use CALCULATE and SAMEPERIODLASTYEAR functions)
  3. Sales Var - calculates sales variance between this year and last year sales
  4. Sales Var % - calculates sales variance between this year and last year sales in percentage (use the DIVIDE function)
- Create Year to Date calculations measures:
  1. YTD Sales - calculates the YTD sales (use the TOTALYTD function).
  2. LY YTD Sales - calculates last year YTD sales
  3. YTD Sales Var - calculates sales variance between this year and last year YTD sales
  4. YTD Sales Var % - calculates sales variance between this year and last year YTD sales in percentage
- Create Market Share measures:
  1. Total Own Sales - calculates sales where the products manufacturer is the company (Use the CALCULATE function and filter by Manufacturer)
  2. % Sales Market Share - calculates the percentage of sales of company's manufactured products from the total sales

----
### Module 3: Power BI Desktop Visualization
Visualizing Your Data
Working with Multiple Visualizations

### Module 4: Power BI Service
Working with Power BI Service
Viewing Power BI Dashboard

### Module 5: Working with Excel
Connecting and Collaborating with Excel

### Module 6: Organization Packs, Security and Groups
Working with Others

### Module 7: Direct Connectivity

### Module 8: Developer API

### Module 9: Mobile App


## My notes

Course Progress for Student 'achoczaj'

Your enrollment: Audit track

Course start: 2017.02.20

Course end: 2017.

Course progress: Total result = %
