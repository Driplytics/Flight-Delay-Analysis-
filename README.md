# Flight Delay Analysis
![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/WAITING%20DELAY.jpg)
##   Overview
As a Capstone project for Microsoft Organized NG30DaysofLearning Training. It's required that I apply the Analytical skills I learnt during the course of the training, to tell a story about Flight Delay Experiences.  
My Objective is to perform an Exploratory Data Analysis on a flight Experience Dataset, to find insights with delayed flights, lookout for patterns common to them and identity possible causes of flight delays. I made use of the Best Available Tools and Resources to Explore and present insights using Data Visualization  

##  Tools


*  Microsoft Excel - For Creating custom tables, since some of the External Datasets were neither in CSV nor JSON format, before importing the Data into Power BI. Though I can still do this on Power BI, but Microsoft Excel gives me more flexibility.

*  Microsoft Power BI - The Primary tool I used for my Analysis and report building. It contains a vast library of tools for Visualization.

*  Adobe illustrator - I used illustrator as a supporting tool for design. I Used Adobe illustrator in Designing icons and wireframes that I built my report with. 




##  Resources

* Flight Data source : 
<https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Airline%20Project/Airlines.csv>  ![Flight Data image](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Dataset.png)

*  ####  Overlayed Data : 
*  Airport Names: 
<https://datahub.io/core/airport-codes>  
![Airport Names](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Airport%20Name%20Data.png)  
*  Airline Names : 
<https://gist.github.com/AndreiCalazans/390e82a1c3edff852137cb3da813eceb>. ![Airline Names Table](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Airline%20Table.png)





##  Where is the Data? 
The Data used for my Analysis were from 3 Different sources (see **Resources**), the main flight data has Airport and Airline codes as a means of identity, hence the need to source for external Data set that would  overlay these codes and provide the names of Airlines, Airport and their location, by creating a Data model  between the 3 tables. 

##  Project Flow

![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Project%20flowArtboard%201.png)
1.__Data Cleaning :__ The Flight Data is a cleaned up Dataset, hence required no further cleaning, except some necessary transformations. On the other hand, the overlay Data needed some cleaning and transformation to remove unneeded columns from the Table. 
 
___
 ![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Flight%20Experience%20Context.jpg)
2.__Defining the Context and Objectives:__ Before starting any Analysis, I like to gain clarity from the start. And I achieve this by defining the context of Who my audience is, What is required of me, Why It's important to them and How I can meet this requirements. This helps me to understand the problem and my Objectives.
___

3.__Data Overlay and and Reverse Geocoding :__ Here's where I made a good use of external Dataset, using IATA codes for airports and airlines in the flight Data to get the names airlines, airports and it's location from an external Dataset.

___

4.__Data Modeling__ :I built Data model using Data Resources I gathered; Flight Data, Airport data and Airline Data to build a seamless Data model.

___
5.__Way Finding/Thought Process__: Before I start Analyzing my dataset, i love to spend time to think through, and go through a discovery session with the various entities I would work with, connect the dots while taking notes of possible relationships that could exists between different entities and write them down with pen and paper. This is the bedrock of my Analysis. Because here I look out for possible insights the connections could provide.  It's was at this stage that I got the idea about making a move to get an External Datasets, before going to Google about flight codes, which I didn't know existed. 

___
6.__Analysis & Visualization__: At this stage I already have a plan and things to look out for on my Analysis which was conceived during my discovery session. So I just explore the Dataset and note down patterns I find, then employ the right visual tools that fit the context to present my Findings. 







 


















