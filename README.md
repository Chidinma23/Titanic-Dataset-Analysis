# Titanic-Dataset-Analysis
![Screenshot 2023-04-15 123052](https://user-images.githubusercontent.com/115046602/232221410-8efbd934-918c-452c-96ab-9b222694b3a7.png)
# Introduction
# Project Overview
# Data Sourcing
Data was extracted and downloaded in Excel format
The dataset was loadedinto the power Navigator first to show us a preview of what our data is about before we begin editing which is later loaded into PowerQuery editor.
# Data Cleaning Process
There are two data in this set: Passengers and Comment. The comment tells us what we have in the Passenger ID. The survive column was changed form 0 and 1 to Dead and Survived. Pclass column was changed to Passenger class and 3,2,1 changed to 3rd, 2nd and 1st class.The name column was split by delimiter to give Title, first name and other name, sex was renamed to Gender and capitalized the initials of "male" and "female". A custom column was created and named 'Family size' containing the total number of relatives from the same family onboard. The Embarked column was transformed form 'S' 'C' 'Q' to 'Southampton' 'Cherburg' and 'Queenstown'. Excess white spaces were removed from each of the name column by trimming. Also, data types were changed accordingly. Number of Passengers by age and passenger class: herer an age group were created to be able to separate and see the age group of the passengers, a new group was created from the age data this is done because the age has a sumation symbol and age is actually counted and not summed up; using a bin size of 5 the age was grouped and was represented in aribbon chart to analyze for the number of passengers by age group and passenger class.
