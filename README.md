# Assignment 03 Ensemble Methods Comparison

This repository contains my work for the Ensemble Methods Comparison assignment in my data analytics course. The goal of the project is to predict whether construction project management forms will be closed or remain open by applying three tree based models.

## Dataset
The dataset comes from construction project management forms and includes information such as form type, open actions, total actions, overdue items, documents, images, project, and report group. The target variable is a binary value called is_closed, where one means the form is closed, complete, or resolved and zero means it is still open or ongoing.

## Models Used
Single Decision Tree  
Random Forest  
Gradient Boosting

## Summary of Results
All three models performed strongly with accuracy values between zero point eight three eight and zero point eight four two. The Single Decision Tree achieved the highest recall and the highest F1 score. The Random Forest reached the highest accuracy and precision. Gradient Boosting provided balanced performance and captured complex patterns in the data. The Random Forest is recommended for practical use because it provides dependable performance and clear value for project management.

## Files
ensemble_comparison.ipynb  
