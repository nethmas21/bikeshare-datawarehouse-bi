# BikeShare Data Warehouse & Business Intelligence Solution

## Project Overview

This project presents an end-to-end Data Warehouse and Business Intelligence solution developed using the Capital Bikeshare dataset.

The solution was designed to support analytical reporting and multidimensional analysis using SQL Server, SSIS, SSAS, OLAP operations, and Power BI.

The project includes ETL pipeline development, dimensional modelling, cube implementation, and interactive business intelligence reporting.

---

## Dataset Information

* Dataset Source: Capital Bikeshare
* Total records analyzed: Over 108,000 bike trip records
* Data period: January 2023 – December 2023

The dataset includes:

* Bike trip duration
* User types (member/casual)
* Start and end stations
* Date and time information
* Transaction processing metrics

---

## Technologies & Tools

* SQL Server
* SQL Server Integration Services (SSIS)
* SQL Server Analysis Services (SSAS)
* SQL Server Management Studio (SSMS)
* Power BI
* Microsoft Excel
* XMLA
* Visual Studio

---

## Data Warehouse Design

A star schema dimensional model was designed and implemented.

### Fact Table

* `Fact_Trips`

### Dimension Tables

* `Dim_Date`
* `Dim_Station`
* `Dim_User`

Key concepts implemented:

* Surrogate Keys
* Star Schema Design
* Slowly Changing Dimension (SCD Type 2)
* Role-Playing Dimensions

---

## ETL Pipeline

An ETL pipeline was developed using SSIS to process 12 months of bike-sharing data.

The ETL process included:

* Data extraction from CSV datasets
* Data staging and transformation
* Data cleaning and validation
* Loading dimension tables
* Loading fact tables
* Historical tracking implementation using SCD Type 2

---

## SSAS Cube Implementation

A multidimensional SSAS cube was developed using the BikeDW data warehouse.

### Measures

* Trip Duration
* Transaction Process Time
* Trip Count

### Dimensions

* Date Dimension
* User Dimension
* Start Station
* End Station

A hierarchical Date dimension was implemented:

* Year → Month → Day

---

## OLAP Operations Demonstrated

The following OLAP operations were demonstrated using Excel PivotTables connected to the SSAS cube:

* Roll-up
* Drill-down
* Slice
* Dice
* Pivot

---

## Power BI Reports

Four interactive Power BI reports were developed:

1. Matrix Visual Report
2. Cascading Slicers Report
3. Drill-down Analysis Report
4. Drill-through Navigation Report

Features demonstrated:

* Interactive filtering
* Hierarchical drill-down
* Drill-through analysis
* Dynamic slicers
* Multidimensional reporting

---

## Files Included

* `BikeShare_DW_Report.pdf` → Data warehouse and ETL implementation report
* `BikeShare_BI_Report.pdf` → SSAS, OLAP, and Power BI implementation report
* `Images/` → Star schema, ETL pipeline, OLAP, and dashboard screenshots

---

## Key Skills Demonstrated

* Data Warehousing
* ETL Development
* SSIS
* SSAS
* Power BI
* OLAP Analysis
* SQL Server
* Dimensional Modelling
* Business Intelligence Reporting
* Data Transformation
* Analytical Reporting

---

## Author

Nethma Weerasinghe
