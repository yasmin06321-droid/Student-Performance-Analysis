# Database Setup

## Database Used

The project uses **SQLite** as the database for storing and analyzing
student performance data.

## Data Source

The original student performance data is maintained in an Excel file.

The dataset contains information such as:

- Student ID
- Student Name
- Department
- Attendance Percentage
- Internal Marks
- Assignments Submitted
- Absentees
- Risk Level

## Database Workflow

Excel Dataset  
↓  
SQLite Database  
↓  
Metabase Connection  
↓  
Data Synchronization  
↓  
Student Performance Analysis  
↓  
Visualization and Risk Analysis

## Metabase

Metabase is used as the data visualization and analytics platform.

The SQLite database is connected to Metabase, allowing the student
performance records to be viewed, filtered and analyzed.

## Execution

Metabase was started locally using:

`java -jar metabase.jar`

After starting Metabase, the SQLite database was connected and
synchronized. The student performance table was then analyzed using
Metabase.

## Analysis

The project analyzes student performance based on attendance,
internal marks, assignments and absenteeism.

The data can also be filtered according to the student's risk level.

## Note

The local Metabase application files and `metabase.jar` are not included
in this repository. The repository contains the project dataset,
documentation and execution screenshots.
