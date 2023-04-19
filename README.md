# Titanic-Dataset-Analysis
![Screenshot 2023-04-15 123052](https://user-images.githubusercontent.com/115046602/232221410-8efbd934-918c-452c-96ab-9b222694b3a7.png)
# Introduction
# Project Overview
# Data Sourcing
Data was extracted and downloaded in Excel format
The dataset was loadedinto the power Navigator first to show us a preview of what our data is about before we begin editing which is later loaded into PowerQuery editor.
# Data Cleaning Process
There are two data in this set: Passengers and Comment. The comment tells us what we have in the Passenger ID. The survive column was changed form 0 and 1 to Dead and Survived. Pclass column was changed to Passenger class and 3,2,1 changed to 3rd, 2nd and 1st class.The name column was split by delimiter to give Title, first name and other name, sex was renamed to Gender and capitalized the initials of "male" and "female". A custom column was created and named 'Family size' containing the total number of relatives from the same family onboard. The Embarked column was transformed form 'S' 'C' 'Q' to 'Southampton' 'Cherburg' and 'Queenstown'. Excess white spaces were removed from each of the name column by trimming. Also, data types were changed accordingly. Number of Passengers by age and passenger class: here an age group was created to be able to separate and see the age group of the passengers, a new group was created from the age data this is done because the age has a sumation symbol and age is actually counted and not summed up; using a bin size of 5 the age was grouped and was represented in aribbon chart to analyze for the number of passengers by age group and passenger class.
# Power Query
The data was finally updated to PowerBi for analysis and visualization
The following insights were drawn from the data:
1. Total Number of Passengers
2. Passengers by Gender
3. Number of Passegers by Survival
4. Count of Survival by Embarked and Survival
5. Count of Gender by Gender and Survival
6. Count of Survival by Passenger Class and Survival
7. Count of Passenger Class by Embarked and Passenger Class
8. Number of Passengers by Age Group and Passenger Class
9. Key Influencers to Survival
Interact with my dashboard and report here
# Conclusions
891 Passengers were recorded in this data set and males were more than females with 577 (64.76%) and 314 (35.24%) respectively. Titanic Survival rate is 38.38% with females having survived more than men - 74.2% and 18.89% respectively. For the passenger class, first class passengers had more survival rate than second and third with count of survival being 136.
