# Data Visualization Project

## Data
The data I propose to visualize for my project is: https://gist.github.com/yichenlilyc/e82f39f103162cda7efc2c5662e203fd 

## Prototypes
I've created a proof of concept visualization of this data. It's a Scatter Plot shows the NBA players' Scoring Efficiency. In this scatter plot, darker color shows higher scoring efficiency. 
[![Screen Shot 2021-09-22 at 18 42 54](https://user-images.githubusercontent.com/44181571/134443425-82365ff4-8499-4170-92f6-18dca65c3d31.png)](https://vizhub.com/yichenlilyc/6cf83baf069b47bbb8d766fe02f3eee0)

## Questions and Tasks
The following tasks and questions will drive the visualization and interaction decisions for this project:
* Who are the players that have high scoring/assists/blocks efficiency?
* What is the score distribution in each team?
* Who are the players that are good at field goals/ 3 score field goals?
* 
## Sketches
![IMG_0010](https://user-images.githubusercontent.com/44181571/134444060-b30f9803-a5ad-4604-a058-2d3ef407b733.jpg)
The data is visualized in scatter plot. In the picture, each point represents a player and the color shows the team that the player is in. All the points are interactable, when hovering on the point, the name of the player will come out. Below are selection boxs taht enables users to choose to show or hide the players in specific teams. When the user clicks at the point, it will lead the player to chart 2.
This plot helps answer the first question. The slope of the point represents the efficiency. There is a blue line in the plot showing the mean efficiency.
![IMG_0012](https://user-images.githubusercontent.com/44181571/134444473-0bd7ef99-16f4-415e-91c6-3bc6b81b3788.jpg)
This visualization shows each player's skills. The pie chart shows the losses and wins. All the points and areas are interactable. When hovering on the point/win loss area, the points come out. 
This plot helps answer the second question. In the left plot, the points that are further to the center represent the stronger skill.
![IMG_0014](https://user-images.githubusercontent.com/44181571/134444794-1d061ade-fb14-432c-839d-a20d4feb33a4.jpg)
These two visualizations shows the team status. The bar chart shows the players skill in the team. There is a blue line showing the average in the team. At the top, there are selection boxes that enable users to choose to show/hide specific players. The pie charts shows the wins and losses for each player. The size of the whole circle shows the total games that the player played. The larger the more games the player has played. 
The bar chart helps answer the second and third question. It's easy to find out the player that has the largest bar, which represents for strong skill.

## Open Questions
* I'm not sure whether it is good to use different color to represent different teams. Cause there are 30 teams and I'm concerned about whether it is too much and whether it can make the visualization hard to read.
