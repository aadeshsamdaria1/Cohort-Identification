# Cohort Identification
Name: Aadesh Samdaria

Email: asamdaria@student.unimelb.edu.au

## Problem Description
This project addresses the issue of characterizing and clustering patients who have experienced hypotension, a medical condition characterized by abnormally low blood pressure. Hypotension can manifest in various forms, and clinicians use specific criteria to identify these conditions. To aid medical research and patient care, the project involves the integration of data from different sources and the identification of patients who have experienced significant hypotension events.

## Importance
Understanding hypotension is crucial in the field of healthcare as it can be a symptom of serious medical conditions. By identifying and characterizing hypotension events, we can improve patient care and contribute to medical research. This project is important because it allows us to categorize and analyze patient data for better diagnosis and treatment.

## Solution Overview
The project involves the analysis of healthcare data to identify patients who have experienced hypotension. This includes data from various sources, such as blood pressure measurements, administered medications, and ICD (International Classification of Diseases) codes. The main steps of the solution are:

### Data Collection: 
The project collects data from multiple sources, including blood pressure measurements, administered medications, and ICD codes.

### Data Processing: 
Data is cleaned, filtered, and processed to extract relevant information. This includes identifying blood pressure thresholds and time intervals between measurements.

### Cohort Identification: 
The project identifies patients who have experienced meaningful hypotension events by analyzing the data. This involves matching blood pressure values with specific criteria and medication administration times.

### Data Analysis: 
The project aggregates the data to create a cohort of patients who have experienced hypotension events. It also associates relevant ICD codes with these patients.

## Requirements
To run this project, the following files and data sources are required:

- Access to the MIMIC-IV dataset or relevant healthcare database.
- Code for data collection and processing, as presented in the code snippets.
- Required Python packages and libraries, including NumPy and Pandas.
- SQL queries to retrieve relevant data from the database.

## Core Packages and Versions
- Python 3.10.12
- NumPy 1.23.5
- Pandas 1.5.3
