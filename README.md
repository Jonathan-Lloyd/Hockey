# 2011-2021 NHL Player Analysis



### The NHL?
The National Hockey League (NHL) was formed on November 26, 1917 and only had 8 teams. Since then the NHL has expanded and grown to now include 32 teams across Canda and The United States. Considered by most to premier ice hockey league in the world backed by its talent and revenue. This study will break down the last 10 years of Hockey by statistics and finances.

### Motivation
I have lived in the greater Nashville Area since 1997, I was 10. I grew up playing competitve sports and sport videos games in my childhood. I always have had an interest in understanding the how and why behind how major sport teams. In 1999 the city of Nashville enjoyed its first year as a NHL city and I was introduced to Hockey at the highest level. Since that time I have become and avid fan and played multiple NHL licensed game titles. Ive always enjoyed constructing theoretical teams through videogames respective Franchise game modes 

### The why?
The last two years the Tampa Bay Lighting  have won the league championship, Lord Stanley's Cup. How did this team win in a salary cap league 2 years with a static cap(pandemic)?How did they build their team to get to this point? Now, with my recent studies in data analytics I wanted analyze and present findings from real world sources.

#### I will be taking the last 10 years of hockey data, which will include player stats and salaries and develop a grading system. I will then use this data to determine the following:

* What are the average salaries of the each grade given

* How the top 4 teams of each year(ranked by playoff finish) built their teams.

* I will Define Salary Cap rules that have been collectively bargained.

###### I will provide interactive visualizations in Power Bi and/or Tableau that will be filterable by player, team, ratings

 
### Data search that is as Cold as Ice, was I willing to Sacrifice?
* When I started to gather raw data,I felt webscraping was the route I was going to have to take since I didnt find any APIs or free datasets in my search. Webscraping where it wasnt behind a login or was disallowed quickly became the norm and I worried that my capstone idea would be on ice. So before giving up I looked for an API once more. Turns out there is an undocumented NHL API that was created and luckily someone took upon themselves the arduous task of documenting multiple parameters.
    A huge thanks and shout out to [Drew Hynes](https://github.com/dword4/nhlapi).
    Another thanks to my instructors teaching me API basics so I could even pull what I needed.
    
    
### Getting the Raw data
* So after reading the documention I found the API had mulitple arguments that I was going to use. One for teams rosters, and another for individual players that both fell directly after the orginal API endpoint. I found the player stats were nested in the players arguments but I needed their player id which was nested in the team rosters.
* I first created a loop to run through the api and grab every team's roster with player ids in a given year to create a dataframe..
![player id dataframe](Images/player_id_dataframe.png)



### What this analysis finds


### Sources