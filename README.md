# DataFest: Improving Student Learning Experience

This project was developed as part of the DataFest competition, organized by the **American Statistical Association (ASA)**. The objective is to assist CourseKata, a textbook platform, in understanding how students learn and identifying ways to improve their learning experience.

## Project Overview

The project focuses on analyzing student engagement with the platform and determining which chapters of the textbook are perceived as difficult. Various data science techniques were applied, including data preprocessing, logistic regression, clustering, and data visualization. The ultimate goal is to identify chapter difficulty and propose strategies to enhance the student learning experience.

## Key Findings

Clustering: I grouped students based on their engagement levels to better understand how different types of students interact with the platform (Refer to the `clustering_engagement.Rmd`).

Logistic Regression: I categorized each chapter as either "difficult" or "not difficult" based on various features of student interactions. The logistic regression model helped quantify chapter difficulty (See `Logistic_regression_objective_function.Rmd` for details).

Recommendations for Improving Learning: From both the model and descriptive analytics, I concluded that improving student engagement in difficult chapters requires more interactive media, better chapter design, and a focus on the psychological well-being of students. (Refer to `media_data.Rmd` and `engagement_bar_graph.Rmd`)