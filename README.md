# Census-Data-Analysis-Project
## Overview
This project involves a comprehensive data analysis of a census dataset from a small town located between major cities. The dataset aims to provide accurate population and demographic insights to support governmental planning and investments on an unoccupied plot of land.

## Key Objectives
   * Clean and preprocess raw census data for analytical purposes.
   * Perform exploratory data analysis (EDA) to extract actionable insights.
   * Support strategic decisions such as infrastructure development (e.g., transportation and educational facilities).

## Dataset Summary
The census dataset required significant cleaning due to:
   * Duplicates and missing values
   * Inconsistent entries in categorical columns (e.g., Religion, Marital Status, Occupation)
   * Incorrect datatypes (e.g., Age as string instead of integer)
   * Blank values in essential fields like First Name, Surname, and Age

## Data Cleaning Process
   * Removed duplicate records.
   * Addressed missing values in key columns by applying logical rules (e.g., underage marital status fixes).
   * Standardized categorical variables and corrected typographical errors.

   Introduced new engineered features:
   * Occupation_Category: Grouped occupations into "employed," "unemployed," "student," "retired," and "child."
   * Age_Group: Grouped age into 5-year bands.
   * Household: Defined households using house number and street name.

## Exploratory Data Analysis (EDA)
The following key insights were derived from the cleaned data:
   * Age Pyramid: Revealed a predominance of middle-aged residents (30-49 years) indicating a maturing population.
   * Employment Trends: 53.5% of the population were employed, while 9.57% were unemployed, mostly individuals under 41.
   * Religious Affiliation: 41.1% of the population had no religious affiliation, while Christians accounted for 28.9%.
   * Marital Status Trends: 36.7% were married and 11.97% divorced; divorces were prevalent among women under 50.
   * Housing: Over 62% of homes were under-occupied, suggesting no immediate need for new housing developments.
   * Commuters: More than half of the town’s population were commuters, indicating potential for improving transportation infrastructure.

## Recommendations
Based on the insights:
   * Infrastructure: A train station is recommended to support the town’s commuter-heavy population and boost economic development.
   * Educational Facilities: Increased investment in schooling due to a growing young population (students account for 26.65% of the total).
   * Religious Buildings: No immediate need for additional places of worship due to low demand.
   * Healthcare Facilities: The town does not urgently require new elderly care or emergency medical centers due to the relatively healthy and young population.
