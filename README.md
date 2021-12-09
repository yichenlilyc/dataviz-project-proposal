# Data Visualization Project

## Project Description
In this project, the [NBA Players' state](https://gist.github.com/yichenlilyc/e82f39f103162cda7efc2c5662e203fd) in 2020~2021 season is visualized. The original data is collected from the [NBA official website](https://www.nba.com/stats/players/traditional/?sort=TD3&dir=-1). In the project, the dataset is visualized in scatter plot, bar chart, spider chart and pie chart. The visualizations are implemented with d3.js and react.js on [VizHub](https://vizhub.com/).

## Dataset
* [NBA Players' State](https://gist.github.com/yichenlilyc/e82f39f103162cda7efc2c5662e203fd)

## Questions and Tasks
The following tasks and questions drive the visualization and interaction decisions for this project:
* Who are the players that have high scoring/assists/blocks efficiency?
* What is the score distribution in each team?
* Who are the players that are good at field goals/ 3 score field goals?

## Prototypes
* NBA players' Efficiency Scatter Plot: In this scatter plot, the representation of y-axis can be changed by te selection box, and darker color shows higher efficiency. 
[![Screen Shot 2021-09-22 at 18 42 54](https://user-images.githubusercontent.com/44181571/145346263-a54e9eb7-e6b7-466b-83ca-ec7ad956e777.png)](https://vizhub.com/yichenlilyc/d692441922ab4bb4ac3e53081d7fe0af)
* LAL NBA Player Scoring Bar Chart: In this chart, the scores are sorted in descending order. The horizontal line depicts the mean score of the team.
[![Screen Shot 2021-10-13 at 14 43 01](https://user-images.githubusercontent.com/44181571/137216684-4c15e5d4-fa78-480d-aaa6-fcfb0e8ca62d.png)](https://vizhub.com/yichenlilyc/0baca9e766834caba2b65d6d6e21b436) 

## Sketches
![IMG_0036](https://user-images.githubusercontent.com/44181571/137221818-8d0fe0d0-fdcc-4ff5-ad55-7dd3c1640279.jpg)
The data is visualized in scatter plot. In the picture, each point represents a player. The red and blue color represents Western and Eastern Team respectively. All the points are interactable, when hovering on the point, the name of the player will come out. 
This plot helps answer the first question. The slope of the point represents the efficiency. There is an orange line in the plot showing the mean efficiency.
![IMG_0038](https://user-images.githubusercontent.com/44181571/137221836-aebc403f-3649-4202-bb4f-e63387f6bd6c.jpg)
This visualization shows each player's skills. The pie chart shows the losses and wins. All the points and areas are interactable. When hovering on the point/win loss area, the points come out. 
This plot helps answer the second question. In the spider plot, the points that are further to the center represent the stronger skill. From this chart, the players strength and weakness can be read easily.
![IMG_0037](https://user-images.githubusercontent.com/44181571/137221860-f53f24aa-24f9-450a-94b3-511cbc308875.jpg)
These two visualizations shows the team status. The bar chart shows the players skill in the team. There is a red horizontal line showing the mean value of the team. The pie charts shows the wins and losses for each player. The size of the whole circle shows the total games that the player played. The larger the more games the player has played. 
The bar chart helps answer the second and third question. The player that has the largest bar has the strongest skill in the team.

## Schedule of the Deliverables
* Visualization 1: Players' efficiency scatter plot. (Oct 15)
  * Create the scatter plot
  * Use differect hue to represent Eastern team and Western team
  * Drop down menu for y axis
  * Create a line for mean efficiency.
* Visualization 2: Player's skill plot. (Nov 24)
  * Create a spider plot for skill analyzation (2 days)
  * Create a bar chart to depict losses and wins (1 day)
  * Drop down menu for Team and Player (1 day)
* Visualization 3: Team analyzation bar chart. (Oct 29)
  * Create the bar chart 
  * Drop down menu for Team and y axis. (1 day)
  * Bar chart for Rebounds (3 day)
* Visualization 4: Team analyzation pie chart. (Oct 15)
  * Create multiple pie charts in one page. (3 days)
  * Drop down menu for Team (1 day)

## Iterations
### NBA Player Efficiency Scatter Plot
In this scatter plot, the efficiency of all the players are depicted. In the plot, each dot represents a player in the league. The hover effect is applied to all the dots. The name of the player pops out when the mouse cursor is on the dot. The drop down menu enables users to choose the representation of the x-axis and y-axis. I used the different color hue to show the efficiency. When the x-axis is set as the average time that the player played in each game, the darker the color shows the higher efficiency.
[![img](https://user-images.githubusercontent.com/44181571/145342614-b0584b3b-e36d-4ed8-8cf9-1adbbbfa6f86.png)](https://vizhub.com/yichenlilyc/7a8c7838797c46f48ce0224661ab3e0c)

### NBA Player Games Played Bar Chart
This iteration describes the players' wins/losses in the team. Instead of using the pie chart as I originally designed in sketches, I used the bar chart to show the total games that the player played and use different color indexes to show the number of wins and losses. The dropdown menu can be used to change the team. The players are ordered decently by the total games they've played during the season.
[![img](https://user-images.githubusercontent.com/44181571/145344500-16e70c41-c8b3-45b9-8f2d-f0913045280a.png)](https://vizhub.com/yichenlilyc/539d25adc25942359d0cd205959603f0?edit=files&file=index.js)

### NBA Players State Bar Chart
In this bar chart, the X-axis Represents the player's name. Users can use the drop down menu to choose the team and filter the data. There is also a dropdown menu for the Y-axis representation. For the rebounds data, the bar is separeated into Offensive Rebounds and Defensive Rebounds. The hover effect is applied to all the bars in the chart. The accurate value will pop out when hovering on the bar. There is also a horizontal line in the chart, showing the mean value of the team. 
[![img](https://user-images.githubusercontent.com/44181571/145344646-bc4316b1-030b-480e-9d67-024781add402.png)](https://vizhub.com/yichenlilyc/584f1db67d254305aec291f72a296c8d?edit=files&file=index.html)

### NBA Players' Skills Chart
There are two plots in this iteration. The left one is a spider chart, which describes the players' performances in gaining points, rebounds, turnovers, blocks, steals and assists. The right one is a pie chart describing the players' total wins and losses during the season. The drop down menu can help quickly filter the players by team. The hover interaction is added to all the dots in the spider chart. When the mouse cursor is on, the accurate number will show up.
[![img](https://user-images.githubusercontent.com/44181571/144335940-b0839f6d-7563-40fa-9428-faab950afc0b.png)](https://vizhub.com/yichenlilyc/825ccc94175143e2add9e45b98efc2d4?edit=files&file=index.js)

## Summary

