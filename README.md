# Airline Passenger Sentiment Analysis

## Table of Contents

- [Introduction](#introduction)
- [Project Summary](#project-summary)
- [Problem Statement](#problem-statement)
- [Business Objectives](#business-objectives)
- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Key Questions Explored](#key-questions-explored)
  - [Key Insights](#key-insights)
  - [Visualizations](#visualizations)
- [Machine Learning Models](#machine-learning-models)
  - [Top Three Models](#top-three-models)
  - [Feature Analysis](#feature-analysis)
  - [EDA Questions](#eda-questions)
  - [Final Conclusion](#final-conclusion)

## Introduction
This project aims to analyze and predict passenger sentiments based on reviews of various airline services. The dataset used contains information about airline reviews, including overall ratings, specific service ratings, traveler types, and more.

## Project Summary
In this sentiment analysis project, we explored a dataset containing airline reviews to gain insights into passenger sentiments. We performed exploratory data analysis (EDA) to understand the distribution of ratings, identify key factors influencing passenger recommendations, and explore patterns among different traveler types.

Following the EDA, we implemented machine learning models, including Logistic Regression, Support Vector Machine (SVM), and K-Nearest Neighbor (KNN), to predict passenger sentiments accurately. The logistic regression model emerged as the top-performing model with the highest accuracy.

## Problem Statement
The main goal of this project is to understand the factors influencing passenger sentiments and build a predictive model to determine whether a passenger would recommend a particular airline based on their reviews. The problem involves classification and sentiment analysis of customer feedback.

## Business Objectives
- Identify key factors contributing to positive or negative passenger sentiments.
- Develop a predictive model to classify reviews and predict recommendations.
- Provide actionable insights to airlines for improving services and customer satisfaction.

## Dataset Overview

The dataset consists of the following columns:

- **airline**: The name of the airline.
- **overall**: Overall rating provided by the reviewer.
- **author**: Author or reviewer's name.
- **review_date**: Date when the review was posted.
- **customer_review**: The actual content of the customer's review.
- **aircraft**: Aircraft type (if available).
- **traveller_type**: Type of traveler (e.g., Solo Leisure, Business, Family Leisure).
- **cabin**: Cabin type (e.g., Economy Class, Business Class).
- **route**: Flight route information.
- **date_flown**: Date when the flight was taken.
- **seat_comfort**: Rating for seat comfort.
- **cabin_service**: Rating for cabin service.
- **food_bev**: Rating for food and beverages.
- **entertainment**: Rating for in-flight entertainment.
- **ground_service**: Rating for ground services.
- **value_for_money**: Rating for value for money.
- **recommended**: Whether the reviewer recommends the airline (yes/no).

## Exploratory Data Analysis (EDA)

### Key Questions Explored
- **1. What is the distribution of overall ratings across different airlines?**
- **2. How do different cabin types correlate with overall satisfaction?**
- **3. Is there a significant difference in ratings between Economy and Business/First Class passengers?**
- **4. What factors contribute most to passenger recommendations?**
- **5. How does the sentiment vary among solo travelers and other traveler types?**

### Key Insights
- **Economy Class Dominance**: Economy class is the most prevalent both in terms of passengers and favorable overall ratings.
- **Balanced Dataset**: The target variable, "recommended," indicates a balanced dataset.
- **Solo Leisure Travelers**: The majority of travelers are solo leisure travelers.
- **Top Reviewed Airlines**: American Airlines, United Airlines, and British Airways receive the most reviews.

### Visualizations
- Visualizations include histograms, bar plots, box plots, pie charts, correlation heatmaps, and pair plots. These provide insights into the distribution of ratings, cabin types, and the relationship between different variables.

## Machine Learning Models

### Top Three Models

1. **Logistic Regression**
   - Achieved the highest accuracy among the experimented models.
   - Identified as the best-performing model for sentiment prediction.

2. **Support Vector Machine (SVM)**
   - Second-highest accuracy in the model evaluations.
   - Provides robust classification performance.

3. **K-Nearest Neighbor (KNN)**
   - Third-highest accuracy in the model evaluations.
   - Offers a reliable approach for sentiment analysis.

### Feature Analysis
- Overall rating and value for money were identified as crucial factors influencing predictions.

### Final Conclusion
The EDA provided valuable insights into passenger demographics, preferences, and sentiment. Leveraging the top-performing logistic regression model, airlines can focus on enhancing specific services like cabin comfort and value for money to improve overall customer satisfaction and increase positive recommendations.

#
