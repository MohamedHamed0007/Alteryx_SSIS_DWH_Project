# Alteryx_SSIS_DWH_Project
The Dataset contains information on the performance of high school  students in mathematics, including their grades and demographic  information. The data was collected from three high schools in the United  States  and The task is to divide the data into two half and the first half of data and work on SSIS and second half of data and work on Alteryx

two parts to implement in the project:
o Using Alteryx
o Using SQL SERVER Integration Services (SSIS)

Main topics:
 Extract data from Dataset(The performance of high school  students in mathematics)
 Make Transformation
 Load data in the destination
 Construct Star schema
 Make analysis on star schema using Power BI
 Write a documentation

Project in detail:
o Use Alteryx and add Record ID to the data set to can split it
o Use Alteryx to split dataset records into half and load them in two
different destinations. (based on Record Id if even or odd)
o First and second halves destinations will be in Excel format
 For the first half, we will use Alteryx and for the second half we will use SSIS
 I do The same transformation on the two halves but each on its tool (Alteryx - SSIS)
 Transformations  uses:
o 1: filter records on a specific condition (Gender: male or female)

o 2: choose any string column and uppercase the first character only
o Third: split any column into columns
o Fourth: replace any white spaces with an underscore for any string column

 Depending on the first point (1) in transformation, each half will be
divided again into two parts.
o First Half (part 1 and part 2)
o Second half (part 1 and part 2)
 we will have 2 destinations.
o Load part 1 from the first and second halves in destination 1.
o Load part 2 from the first and second halves in destination 2.
 The two destinations will be in SQL Server.
 Design Star schema with 2 dimensions and load data from any destination into it.

 I use Power BI to generate charts from the star schema (3 charts).
 I Make documentation that includes:
o Short paragraph describing the dataset and its columns
o The components were used in the 2 tools (Alteryx and SSIS)
o Screenshots from each component used
o Decisions should be taken depending on charts results

Note: Documentation is provided with the project (DWdocumentation)
