# Bank Marketing Data Cleaning and Transformation Pipeline

## Live Project

* DataLab Project: [Paste your DataLab link here]
* GitHub Repository: [Repository URL]

## Project Overview

This project demonstrates the extraction, transformation, and loading (ETL) of a bank marketing dataset using Python and Pandas.

The objective was to transform a raw dataset into structured, analysis-ready datasets by cleaning data, standardizing categorical variables, handling missing values, converting data types, and separating the data into logical entities.

## Dataset

The source dataset contains information related to a bank marketing campaign, including:

* Client demographic information
* Marketing campaign interactions
* Economic indicators

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Git
* GitHub

## Data Engineering Tasks Performed

### Data Extraction

* Loaded raw bank marketing data from CSV files.
* Selected relevant fields for downstream processing.

### Data Cleaning

* Standardized categorical values.
* Replaced placeholder values such as "unknown" with null values.
* Renamed and reformatted fields.
* Converted yes/no values into Boolean data types.
* Created properly formatted date fields.

### Data Transformation

The source dataset was split into separate logical datasets:

#### Client Dataset (`client.csv`)

Contains customer demographic information such as:

* Client ID
* Age
* Job
* Marital Status
* Education
* Credit Default Status
* Mortgage Status

#### Campaign Dataset (`campaign.csv`)

Contains marketing campaign interaction data.

#### Economics Dataset (`economics.csv`)

Contains economic indicators relevant to campaign performance.

### Data Loading

The transformed datasets were exported as separate CSV files for downstream analytics and reporting.

## Project Outputs

* `client.csv`
* `campaign.csv`
* `economics.csv`

## Repository Structure

├── notebook.ipynb
├── bank_marketing.csv
├── client.csv
├── campaign.csv
├── economics.csv
└── README.md

## Key Skills Demonstrated

* ETL Development
* Data Cleaning
* Data Transformation
* Data Validation
* Data Modeling
* Python Data Processing
* Version Control with Git


