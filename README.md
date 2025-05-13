
# Open Tools scripting assignment : CITS4407


**Author:** Rajashwi Shrestha  
**Student ID:** 23929591  
**Unit:** CITS4407 – Open Tool Scripting

## Overview

This repository contain three bash script , each has single purpose. It process and analyse board Games Geek dataset from kaggle. The main Task are:

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

## How to Use
Firstly we need to make sure script are executable.

```bash
chmod +x empty_cells preprocess analysis
```

Then we can simply run the script with the dataset.For example taking sample.txt

```bash
./empty_cells sample.txt
```

Data preprocessing the dataset

```bash
./preprocess sample.txt > sample.tsv
```

Analysis the dataset.

```bash
./analysis sample.tsv
```
