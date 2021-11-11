# Data Visualization Project

## Data
The data I propose to visualize for my project is: https://gist.github.com/yichenlilyc/e82f39f103162cda7efc2c5662e203fd 

## Prototypes
* NBA players' Efficiency Scatter Plot: In this scatter plot, the representation of y-axis can be changed by te selection box, and darker color shows higher efficiency. 
[![Screen Shot 2021-09-22 at 18 42 54](https://user-images.githubusercontent.com/44181571/134443425-82365ff4-8499-4170-92f6-18dca65c3d31.png)](https://vizhub.com/yichenlilyc/d692441922ab4bb4ac3e53081d7fe0af)
* LAL NBA Player Scoring Bar Chart: In this chart, the scores are sorted in descending order. The horizontal line depicts the mean score of the team.
[![Screen Shot 2021-10-13 at 14 43 01](https://user-images.githubusercontent.com/44181571/137216684-4c15e5d4-fa78-480d-aaa6-fcfb0e8ca62d.png)](https://vizhub.com/yichenlilyc/0baca9e766834caba2b65d6d6e21b436) 

## Questions and Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:
* Who are the players that have high scoring/assists/blocks efficiency?
* What is the score distribution in each team?
* Who are the players that are good at field goals/ 3 score field goals?

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
This iteration describes the players' wins/losses in the team. Instead of using the pie chart, I used the bar chart to show the total games that the player played and use different color indexes to show the number of wins and losses.
[![img](https://user-images.githubusercontent.com/44181571/139180976-ec0a9197-663f-4e8e-877d-2d8dccba780b.png)](https://vizhub.com/yichenlilyc/539d25adc25942359d0cd205959603f0?edit=files&file=index.js)

This iteration describes the players' state in Bar chart. In this chart, the X-axis Represents the player's name. Users can use the dropdown menu to choose the team and filter the data. There is also a dropdown menu for the Y-axis representation. For the rebounds data, the bar is separeated into Offensive Rebounds and Defensive Rebounds.
[![img](https://user-images.githubusercontent.com/44181571/141229232-c81b2f41-e227-4d7a-a842-8defe4ba5f22.png)](https://vizhub.com/yichenlilyc/584f1db67d254305aec291f72a296c8d?edit=files&file=index.html)





