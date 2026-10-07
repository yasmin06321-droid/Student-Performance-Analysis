# Student Performance Analysis

## 📌 Project Overview

Student Performance Analysis is a data analytics project developed to
analyze student academic performance using attendance, internal marks,
assignment submission and absenteeism.

The project uses **SQLite** for data storage and **Metabase** for
interactive data analysis and visualization.

The system helps identify students based on their performance and
risk level, making it easier to understand students who may require
additional academic attention.

---

## 🎯 Objectives

- Analyze student academic performance.
- Store student data using SQLite.
- Connect the database with Metabase.
- Analyze attendance and academic performance.
- Identify students based on risk level.
- Create visualizations for better understanding of the data.

---

## 🛠️ Technologies Used

- **Excel** – Dataset preparation
- **SQLite** – Database storage
- **Metabase** – Data analysis and visualization
- **SQL** – Database querying and analysis

---

## 📊 Dataset

The project uses a student performance dataset containing information
such as:

- Student ID
- Student Name
- Department
- Attendance Percentage
- Internal Marks
- Assignments Submitted
- Absentees
- Risk Level

The original dataset is available in the `dataset` folder.

---

## 🗄️ Database

SQLite is used to store the student performance data.

The database workflow is:

Excel Dataset  
↓  
SQLite Database  
↓  
Metabase  
↓  
Data Analysis  
↓  
Visualization

Details about the database setup are available in:

`database/database_setup.md`

---

## 📈 Metabase Analysis

Metabase is used to connect to the SQLite database and analyze the
student performance data.

The analysis includes:

- Viewing student records
- Filtering student data
- Analyzing attendance
- Analyzing internal marks
- Reviewing assignment submission
- Analyzing absenteeism
- Filtering students according to risk level
- Creating data visualizations

---

## ⚙️ Project Execution

### Step 1 – Prepare Dataset

The student performance dataset is maintained in Excel format.

### Step 2 – Create SQLite Database

The student performance data is stored in a SQLite database.

### Step 3 – Start Metabase

Metabase is started locally using:

```bash
java -jar metabase.jar
### Step 4 – Connect Database

The SQLite database is connected to Metabase.

### Step 5 – Synchronize Data

Metabase synchronizes the database and loads the student performance
data.

### Step 6 – Analyze Data

The student records are viewed and analyzed using Metabase.

### Step 7 – Risk Analysis

Student records can be filtered according to their risk level.

### Step 8 – Visualization

Metabase visualization tools are used to understand student performance
and identify patterns in the dataset.
