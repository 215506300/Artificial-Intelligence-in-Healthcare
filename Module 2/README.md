# Assignment 2: Healthcare Datasets

# Overview
This assignment introduces foundational concepts in healthcare data analysis by working with a structured mock dataset representing outpatient clinic visits. The task focuses on calculating basic descriptive statistics, specifically the average age and average heart rate of patients. These calculations demonstrate how numerical variables within healthcare datasets can be used to generate meaningful insights that support clinical decision making and future AI applications. The assignment aligns with Module 2, which emphasizes understanding healthcare data sources, key databases, and the importance of accurate data interpretation.

# Objectives
This assignment fulfills several key learning objectives of the course.
It demonstrates the ability to
* Interpret structured healthcare datasets
* Identify relevant numerical variables for statistical analysis
* Apply basic statistical methods to derive summary metrics
* Understand how descriptive statistics support clinical and operational insights
* Present results clearly and professionally using appropriate formatting and documentation

# Dataset Description
The dataset contains five patient records with demographic information, visit details, and clinical measurements. For the purpose of this assignment, the variables of interest are
* PatientID
* Age
* HeartRate

These variables allow the calculation of average age and average heart rate, which are commonly used indicators in population health analysis and clinical monitoring. The dataset reflects realistic outpatient visit information, including blood pressure, BMI, smoking status, chronic conditions, and follow up recommendations, demonstrating the breadth of data typically captured in healthcare settings.

# Methods and Approach
The dataset was provided in CSV format. It was converted into a spreadsheet file to facilitate analysis using Microsoft Excel. The approach included the following steps.
* Importing the CSV data into Excel
* Identifying the numerical columns required for analysis
* Applying Excel’s AVERAGE function to compute summary statistics
* Verifying that the selected cell ranges corresponded accurately to the dataset

The formulas used were
* Average Age: =AVERAGE(C2:C6)
* Average Heart Rate: =AVERAGE(K2:K6)

This method reflects standard introductory data analysis practices used in healthcare analytics and prepares learners for more advanced statistical and machine learning techniques.

# Results and Interpretation
The calculations produced the following results.
* The average age of the five patients reflects the general age distribution of the sample population.
* The average heart rate provides a basic indicator of cardiovascular status across the group.

These descriptive statistics demonstrate how even small datasets can provide meaningful insights. In clinical settings, average age may inform risk stratification, while average heart rate may support early detection of abnormalities. In AI applications, such numerical features often serve as inputs for predictive models that estimate disease risk, identify patterns, or support clinical decision making.

# Significance in Healthcare Data Analysis
This assignment reinforces the importance of understanding how healthcare data is structured and how numerical variables contribute to clinical insights. Basic statistical calculations form the foundation for more advanced analytics, including machine learning and deep learning models. Accurate computation and interpretation of descriptive statistics ensure that downstream analyses remain reliable and clinically meaningful. This exercise also highlights the importance of data quality, proper formatting, and consistent variable definitions, all of which are essential for AI systems trained on healthcare data.

# Challenges and Insights
Working with healthcare datasets requires attention to detail, especially when selecting variables and verifying data ranges. Even simple calculations can be affected by formatting inconsistencies or incorrect cell references. This assignment demonstrates the importance of clean data preparation and careful validation. It also illustrates how introductory statistical methods serve as a bridge between raw clinical data and more complex analytical techniques used in AI driven healthcare systems.

# Key Takeaways
* Healthcare datasets contain diverse variables that support clinical and analytical tasks.
* Basic descriptive statistics provide essential insights into patient populations.
* Accurate data handling is critical for both manual analysis and AI model development.
* Understanding dataset structure prepares learners for more advanced healthcare analytics.
