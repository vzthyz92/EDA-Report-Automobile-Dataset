# Automobile Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an automobile dataset using Python. The goal was to clean, transform, and analyze the dataset to uncover insights related to vehicle pricing, fuel efficiency, engine performance, and manufacturer trends.

The project demonstrates practical data analysis skills including:

* Data cleaning and preprocessing
* Handling missing values
* Feature transformation
* Exploratory analysis
* Data visualization
* Business insight generation

-------------------------------------------------------

## Objectives

The main objectives of this project were to:

* Clean and prepare a raw automobile dataset for analysis
* Identify relationships between vehicle attributes
* Compare expensive vs affordable vehicles
* Analyze fuel efficiency across manufacturers
* Investigate engine size and horsepower trends
* Visualize key findings using charts and graphs

-------------------------------------------------------

## Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plotting
* **Jupyter Notebook**

--------------------------------------------------------------------------------------------------------

## Dataset Information

The dataset contains information about various automobiles, including:

* Manufacturer
* Body style
* Engine size
* Horsepower
* Fuel efficiency (city/highway MPG)
* Vehicle price
* Fuel type
* Drive wheels
* Dimensions and specifications

Initial dataset size:

* **205 rows**
* **26 columns**

----------------------------------------------------

## Data Cleaning Process

Several preprocessing steps were performed to improve data quality:

### Data Cleaning Tasks

* Replaced `?` placeholders with proper `NaN` values
* Removed unnecessary columns:

  * `normalized-losses`
  * `symboling`
* Removed duplicate records
* Dropped rows containing missing values
* Converted numerical columns to appropriate data types

### Final Dataset Improvements

* Cleaner and more reliable dataset
* Consistent numerical formatting
* Improved suitability for analysis and visualization

----------------------------------------------------

## Exploratory Data Analysis

The project explored multiple business and analytical questions.

### 1. Most Expensive Vehicles

Analyzed the top 5 most expensive vehicles and compared:

* Price
* Fuel efficiency
* Body styles
* Horsepower

### 2. Least Expensive Vehicles

Investigated affordable vehicles and compared their MPG performance against expensive vehicles.

### 3. Fuel Efficiency Analysis

Calculated and visualized:

* City MPG
* Highway MPG
* Average MPG by manufacturer

### 4. Engine Performance

Identified vehicles with:

* Largest engine sizes
* Highest horsepower

### 5. Manufacturer Analysis

Explored:

* Which manufacturers had the most models
* Which manufacturers produced the most fuel-efficient vehicles

----------------------------------------------------

## Key Insights

### Fuel Efficiency vs Price

The analysis showed that:

* More expensive vehicles generally had **lower fuel efficiency**
* Affordable vehicles tended to provide **better MPG performance**

### Manufacturer Trends

* Certain manufacturers consistently produced more fuel-efficient vehicles
* Some manufacturers dominated the dataset with a larger variety of car models

### Engine Size Relationship

Vehicles with larger engines generally showed:

* Higher horsepower
* Lower fuel efficiency
* Higher prices

----------------------------------------------------

## Visualizations Included

The notebook contains several visualizations, including:

* Bar charts
* Line plots
* Correlation analysis
* Comparative fuel efficiency charts
* Manufacturer comparison graphs

These visualizations help communicate trends and support analytical conclusions.

----------------------------------------------------

## Example Questions Answered

* Which are the 5 most expensive cars?
* Which manufacturers produce the most fuel-efficient vehicles?
* Which vehicles have the largest engines?
* How does fuel efficiency compare between luxury and budget vehicles?
* Which manufacturer has the most vehicle models in the dataset?

----------------------------------------------------

## Skills Demonstrated

This project demonstrates proficiency in:

* Data cleaning and wrangling
* Exploratory Data Analysis (EDA)
* Data visualization
* Statistical reasoning
* Python programming
* Business insight communication

----------------------------------------------------

## Future Improvements

Potential improvements for the project include:

* Building predictive models for vehicle pricing
* Performing advanced statistical analysis
* Creating interactive dashboards using Plotly or Power BI
* Adding machine learning algorithms
* Deploying visualizations to the web

----------------------------------------------------

## About This Project

This project was completed as part of a practical data analysis exercise to strengthen data science and analytics skills using real-world automotive data.

It highlights the ability to work with messy datasets, extract meaningful insights, and communicate findings effectively through visual storytelling.
