# Flight Delay Analysis
![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Delayed.png)
   ## Table of Contenets  
   - [Overview](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#overview)  
   - [Tools](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#tools)  
   - [Resources](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#resources)
   - [Where is the Data ?](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#where-is-the-data)
   - [Project flow](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#project-flow)
   - [Remarks](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#remarks)
   - [The Big Idea](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#the-big-idea)

##   Overview
As a Capstone project for a Microsoft Organized NG30DaysofLearning Training. It's required that I apply the Analytical skills I learnt during the course of the training, to tell a story about Flight Delay Experiences.  
My Objective is to perform an Exploratory Data Analysis on a flight Experience Dataset, to find insights with delayed flights, lookout for patterns common to them and identity possible causes of flight delays. I made use of the Best Available Tools and Resources to Explore and present insights using Data Visualization  

##  Tools


*  Microsoft Excel - For Creating custom tables, since some of the External Datasets were neither in CSV nor JSON format, before importing the Data into Power BI. Though I can still do this on Power BI, but Microsoft Excel gives me more flexibility.

*  Microsoft Power BI - The Primary tool I used for my Analysis and report building. It contains a vast library of tools for Visualization.

*  Adobe illustrator - I used Adobe illustrator as a supporting tool for design. I Used Adobe illustrator in Designing icons and wireframes that I built my report with. 




##  Resources

* Flight Data source : 
<https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Airline%20Project/Airlines.csv>  ![Flight Data image](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Dataset.png)

####  Overlayed Data :   
   *  Airport Names:  
<https://datahub.io/core/airport-codes>  
![Airport Names](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Airport%20Name%20Data.png)  
*  Airline Names : 
<https://gist.github.com/AndreiCalazans/390e82a1c3edff852137cb3da813eceb>. ![Airline Names Table](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Airline%20Table.png)





##  Where is the Data? 
The Data used for my Analysis were from 3 Different sources (see [Resources](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/README.md#resources)), the main flight data has Airport and Airline codes as a means of identity, hence the need to source for external Datasets that would  overlay these codes and provide the names of Airlines, Airport and their location, by creating a Data model  between the 3 tables. 

##  Project flow
![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Project%20flowArtboard%201.png)
1.__Data Cleaning :__ The Flight Dataset is a cleaned up Dataset, hence required no further cleaning, except some optional transformations. On the other hand, the overlay Data needed some cleaning and transformation to remove unneeded columns from the Table. 
 
___

2.__Defining the Context and Objectives:__ Before starting any Analysis, I like to gain clarity from the start. And I achieve this by defining the context of Who my audience is, **What** is required of me, **Why** It's important to them and **How** I can meet this requirements. This helps me to understand the problem and my Objectives.  
    ![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Flight%20Experience%20Context.jpg)
___

3.__Data Overlay and and Reverse Geocoding :__ Here's where I made a good use of external Dataset, using IATA codes for airports and airlines in the flight Data to get the names of Airlines, Airports and it's location from an external Dataset.

___

4.__Data Modeling__ :I built a Data model using the Data Resources I gathered; Flight Data, Airport data and Airline Data to build a seamless Data model.

___
5.__Way Finding/Thought Process__: Before I start Analyzing my dataset, i love to spend time to think through, and go through a discovery session with the various entities I would work with, connect the dots while taking notes :memo: of possible relationships that could exists between different entities and write them down with pen and paper. This is the bedrock of my Analysis. Because here I look out for possible insights the connections could provide.  It's was at this stage that I got the idea about making a move to get an External Datasets, before going to Google about Airline codes, which I never knew existed. 

___
6.__Analysis & Visualization__: At this stage I already have a plan and things to look out for on my Analysis which was conceived during my discovery session. So I just explore the Dataset and note down patterns I find, then employ the right visual tools that fit the context to present my Findings.  
## Remarks 
   *Some of the insights Generated are stated below*    
>:bulb: **The Delays are proportional to number of flights:**   
   Most Used Flights Experience the Most Delays. They have the greatest number of passengers, they are likely to be overwhelmed sometimes(rush hour) and this could cause Overscheduling of flights or delay from the crew, which eventually results to flight delays. This shows delay is likely due to congestions.    

 ![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Airline%20Review.png)
```

```

>:bulb: **Busiest Airports recorded the highest number of flights, and also the higest number of Delays:**  
    A crowded or exceptionally busy airport can have planes lined up on the runway waiting to take off. which causes Airport Congestion. Most times Congestions are common with busy Airports.  
  
 ![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/airports%20review.png)  
 ```
 
 ```
> :bulb: **Number of flights are less on the weekends, and it clearly reflects on the number of delays recorded as the weeks comes to an end:**  
> Flight delays tends to reduce as weekends approaches, when flight Activities are getting low.  

 ![](https://github.com/Driplytics/Flight-Delay-Analysis-/blob/main/Weekends%20Review.png)
 
 ## The Big Idea 
 **From My Analysis, i found that Air Traffic/Congestion is common with delayed flights hence it's a major contributor to the Flight Delays Recorded.**

 <center> Thank you :👋: </center>




 


















