# Data-For-Social-Good-Project-APCSA-

# Unit 3 - Data for Social Good Project

## Introduction

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need.

## Requirements

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program:
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors.
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about.
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs.
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset).
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions.

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As a veteranarian, <br> 
> I want to make an app that can quickly predict an animals disease based on symptoms and specifications, <br> 
> so that I can save more animals lives.

## Dataset 

[Animal Disease Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/shijo96john/animal-disease-prediction)

Columns :
animal_type - A string data type representing the animals type (dog, cat, pig, etc)
gender - A string data type representing the animals gender (male, female)
symptom1 - A string data type representing the animals first symptom (coughing, fever, lethargy, etc)
symptom2 - A string data type representing the animals second symptom (diarrhea, sneezing, nasal discharge, etc)
disease_prediction - A string data type representing the predicted disease of the animal (parvovirus, kennel cough, leukemia, etc)

## UML Diagram 

<img width="601" height="248" alt="image" src="https://github.com/user-attachments/assets/b18dc37c-bad5-40ba-83ef-f2489e0bb666" />

## Description 

My project is a disease prediction app that predicts a disease based on the users specifications about their animal. My app uses multiple text files that are stored into 1d arrays using a loaded constructor. The data in the 1d arrays is used in the findDisease method, which uses a non-enhanced for loop to compare the users input to the dataset in order to return the matching predicted disease. The scanner class is also used in this process where it uses the .nextLine and .toLowerCase methods to store the users answers (animal type, gender, and symptoms) and make it non case sensitive after the user is prompted a question. Our chosen dataset was the animal disease prediction dataset off kaggle, and we chose to take the animal_type, gender, symptom1, symptom2, and disease columns, which mentioned earlier, were then stored into 1d arrays. Our project addressed the users goals by being able to quickly predict diseases based on information about their pet, afterwards informing the user the disease their pet has.

Write a description of your project here. In your description, include as many vocab words from our class to explain your User Story, the chosen dataset and how your project addressed that users goals. If your project used the Scanner class for user input, explain how the user will interact with your project.
