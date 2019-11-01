<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
Alex Navarro Llecha
&
Vladimir Autier

Ironhack Barcelona/Data Analytics

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description

We chose the topic of unemployment in Barcelona. It is one of the main economical topics of our society. We tried to understand how unemployment was spread throughout Barcelona looking at the values in each district/neighborhood.Moreover, we looked over the differences between male and female unemployment over a period of 5 years(2013-2017) and tried to get some interesting information from it.

## Questions & Hypotheses

We tried to anser to the following questions:

Which district in Barcelona has the highest unemployment rate?

What is the evolution of unemployment since 2013/2017?

Do we have more male of female unemployed?

On average which is the month of the year where we register the most unemployment?

When was the worst year for unemployment?
Total average of year and each year
How is the unemployment distribute in the main areas of barcelona?
Which one has the highest rate?
    the min and max of all their years?
    how is the worse district distrubute?
    same for best one


extra question: does inmigration has something to do about it?
    look for the worst and best district in their nationalities

## Dataset

We used the unemployment table given by Ironhack teachers. The data given shows the number of unemployed female and male from 2013 to 2017 in terms of district and neighborhood.


## Database

The structure of our database is divide into 3 tables. The main one which is the whole table of data and then :one with districts and one with neighborhoods. They relate to eachother trought neighboorhood code and district code.

## Workflow

First of all we tried to see the main trends into the table of data. We saw that to understand the table it was usefull to separate it in Genders,Districts,Years. Looking at those different columns gave us the insight needed to perform an analysis of Barcelona's unemployment. We then decided to spread the work between the two of us. 
Alex: I worked on understanding the unemployment linked with the geography of Barcelona.
Vlad: I worked on the male/female question and the global picture of the numbers.
We did the analysis by importing the table to python and using pandas.
Pandas gave us the tool to manipulate the data and find trends and patterns.


## Organization

We organized the work in several steps:

First we created a Trello board and placed all the tasks we needed to perform into the plateform. 
Then we asked ourselves which questions we wanted to answer.
Lastly we divided the work as I explained in the workflow and we tried to help each other as much as possible.

The repository has both our codes that helped us answer the unemplyment data in Barcelona in the your project file.We also have the datasets that we used in the datasets folder.

Trello_link:https://trello.com/b/LfHiBb2j/project-2
Presentation_link:https://docs.google.com/presentation/d/147Y2-K6BhsGEauZI8ckedw5UcUccsD4TbslSvszweF0/edit?ts=5dbb1f2b#slide=id.g708e223773_1_72

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
