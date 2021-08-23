# DuolingoStories_EN-DE
Selenium automation for stories in Duolingo EN - DE course

# Intro
This project was created to learn more about automation for websites. 

I wished to learn german and automation with Python, so I picked Selenium and Duolingo.
My only goal in this project was (and still is) to learn as much as it possible both in scripting/automation and improving language skills.

I hope maybe somebody will find here something helpful in learning path. 

I started with Firefox webdriver but I choosed Chrome instead to get more efficient results. Then I switched to edge chrominium. 

When I start this project my code was very simple and contains many reoccuring parts of codes. 
On the next stage I started implementing functions. To make some efficiency measures I implement performance operatror on story function.

Previously I use time.sleep() to wait for certain element to appear and continue automation. Then I decide to wait for element to become clickable and then proceed with click action. 

# Structure
1. Import all requred modules
2. define most repeated functions.
3. login to duolingo

Every story contains:
Welcome screen with start button
continue button - is most raeoccuring element in script

