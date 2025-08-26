
# Data Quality & Analysis Project 

**Author:** Rajashwi Shrestha

---

## Project Overview

This project demonstrates  **ability to manage, clean, and analyze large datasets** using Bash scripting and Unix/Linux tools. It simulates real-world data workflows, emphasizing **data quality, preprocessing, and actionable analysis**. This repository contain three bash script , each has single purpose. It process and analyse board Games Geek dataset from kaggle. The main Task are:

### 1.Checking Data quality : By handling empty cells

Here we idebntify the empty field or missing values in the dataset and print the number of mising value per columns

### 2.Cleaning dataset : That include:

 - Convert the semicolon separator to the <tab> character
 - Convert the Microsoft line endings to Unix line endings
 - Change format of floating-point numbers to use ‘.’ rather than ‘,’ as the decimal point.
 - Deal with non-ASCII characters by deleting them from the output. For example CO2 in a game title is rendered as CO. (Hint: one way is to use the tr command.)
 - new unique IDs need to be created for the 16 empty IDs.
 
### 3.Analysis : Here we analyse: 
 - What is the most popular domain and most popular mechanics across the set of games. (Appearance in a given game's list counts as 1.)
 - What is the correlation between publication year and average rating, e.g. newer games being preferred over older ones.
 - What is the correlation between game complexity and average rating.

Key highlights:

* Identifying and handling missing or inconsistent data
* Automating data cleaning and preprocessing pipelines
* Analyzing patterns, trends, and correlations in datasets
* Generating insights that support informed business decisions

---

## Core Features

### 1. Data Quality Check (`empty_cells`)

* Detects missing values across dataset columns
* Summarizes data completeness to ensure integrity before analysis

### 2. Data Cleaning (`preprocess`)

* Converts semicolons (`;`) to tab-delimited format for database readiness
* Standardizes line endings and numeric formats
* Removes non-ASCII characters for consistent data
* Generates unique IDs for missing entries

### 3. Data Analysis (`analysis`)

* Identifies most popular game domains and mechanics
* Computes correlations: publication year vs. average rating, and complexity vs. rating
* Produces actionable insights for dataset-driven decision-making

---

## Skills Demonstrated

* Data integrity checks and quality assessment
* ETL-style preprocessing with Bash and Unix tools
* Data analysis and correlation studies
* Problem-solving and automation with real-world datasets
* SQL and database concepts understanding (applied in preparing clean, tabular data)

---

## How to Use

Make scripts executable:

```bash
chmod +x empty_cells preprocess analysis
```

**Step 1 – Check data quality**

```bash
./empty_cells sample.txt
```

**Step 2 – Clean the dataset**

```bash
./preprocess sample.txt > sample.tsv
```

**Step 3 – Analyze the dataset**

```bash
./analysis sample.tsv
```

---

## Outcome

Through this project, I successfully demonstrated my ability to:

* Ensure **data accuracy and integrity** in messy datasets
* Implement **data preprocessing pipelines** similar to ETL processes
* Extract **meaningful insights** to inform strategic decisions
* Handle complex datasets efficiently, preparing them for further **analysis or visualization**

