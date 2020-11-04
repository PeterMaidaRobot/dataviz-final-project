# Data Visualization Project

## Data

This data shows the number of deaths by suicide, firearms, and alcohol based on age group, race, and sex.

Source:
Data World
[Suicide Deaths by Age, Race, and Sex](https://data.world/healthdatany/j6fz-a4ta/workspace/file?filename=vital-statistics-suicide-deaths-by-age-group-race-ethnicity-resident-county-region-and-gender-beginn-1.csv)


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What ages have the highest suicide rates?
 * What ethnicities have the highest suicide rates?
 * What ages have the highest firearm deaths?
 * What ethnicities have the highest firearm deaths?
 * What ages have the highest alcohol-related deaths?
 * What ethnicities have the highest alcohol-related deaths?
 * How does sex relate to the type of death (firearm, alcohol, suicide)?
 * How do these trends change over time? Do death rates go up or down for certain groups?


## Sketches

![Sketch2](https://user-images.githubusercontent.com/23406389/94642146-57c61b80-02b1-11eb-98e3-1a1147c8d103.png)

On the top of this sketch, we can see the amount of deaths over time, along with the breakdown into various categories.
On the bottom of this sketch, we can see donut chart breakdowns across various groups.


## Prototypes

I’ve created a proof of concept visualization of this data with the Vega-Lite-Api. It's a bar graph and it shows the number of firearm deaths over time, split among sex.

[<img width="956" alt="Screen Shot 2020-09-30 at 12 13 58 AM" src="https://user-images.githubusercontent.com/23406389/94642389-f783a980-02b1-11eb-8d6a-afa3d0f93256.png">](https://vizhub.com/PeterMaidaRobot/35ffbebba3f14ef295ee210de4d77c15)

I've also created a stacked bar/"line" graph with the Vega-Lite-Api that shows the numbers of deaths over time broken down by each cause.

[<img width="954" alt="Screen Shot 2020-09-30 at 12 14 10 AM" src="https://user-images.githubusercontent.com/23406389/94642413-0702f280-02b2-11eb-82e4-52aefb5ddc88.png">](https://vizhub.com/PeterMaidaRobot/a262ae234afd4ab59cae693467e000c4)

I then transitioned to working with D3 and React. This is a scatter plot that shows the number of different deaths with each data point representing a different group of sex, ethnicity, and age group. These points are colored differently for males and females.

[<img width="939" alt="Screen Shot 2020-11-04 at 1 59 35 AM" src="https://user-images.githubusercontent.com/23406389/98079287-851e6000-1e41-11eb-8ae6-f6da1da3e5fa.png">](https://vizhub.com/PeterMaidaRobot/92348f1327074da9be2f755f97d9422f)

This is a line graph in D3 and React. It shows the trend of different deaths over time for all classifiers. Each line is a different death type, but each line represents all of the sexes, ehtnicities, and age groups.

[<img width="947" alt="Screen Shot 2020-11-04 at 1 59 15 AM" src="https://user-images.githubusercontent.com/23406389/98079236-7637ad80-1e41-11eb-9a2f-7ba916ce6988.png">](https://vizhub.com/PeterMaidaRobot/66c101c3e841438aa55576f553c61646)



## Final Visualizations

This is the final D3 and React visualization. It is a stacked line graph that shows the trend of each death type over time. If a viewer wishes to interact with the visualization, they may filter by different sex, ethnicity, and age group. The user may also hover over the legend and the corresponding area will be highlighted out among the rest.

This visualization answers the question of which deaths change over time. It shows the total number of deaths when the entire area is used. Different questiosn can be asked by the viewer when they filter the data and view the corresponding trends.

[<img width="958" alt="Screen Shot 2020-11-04 at 1 50 39 AM" src="https://user-images.githubusercontent.com/23406389/98078555-4a67f800-1e40-11eb-8a36-0b72e0adb306.png">](https://vizhub.com/PeterMaidaRobot/4c680aa6f20c45f8962209ef7dd07fed)

This is the start of the pie chart breakdown I was driving towards. The label formatting is still in a prototype stage, but it is effective in showing the data. This visualization answers the question that both sexes have the same general breakdown of death type where there are the most Alcohol deaths, followed by Alcohol and Suicides. It shows that Females have about 75% Alcohol deaths whereas Males have had about 60% Alcohol deaths. Another thing this visualization shows is the breakdown of each death type by sex. In all three death types, there are siginificantly more male deaths than female deaths, off of the death count used in this study. With the alcohol-related-deaths, we see that there is a closer number of female deaths to male deaths.

[<img width="957" alt="Screen Shot 2020-11-04 at 1 51 04 AM" src="https://user-images.githubusercontent.com/23406389/98078582-58b61400-1e40-11eb-8a5e-fc43305f22b0.png">](https://vizhub.com/PeterMaidaRobot/7d7cb1448b214c33bf8dac2ffac183f0)


## Open Questions

I am unsure of the most interesting and efficient way to describe all of this data at once.


## Interactions Ideas

Potential interactions can include:
* A menu on the stacked line chart to filter by the different types of (suicide, firearm, alcohol).
* One pie graph that can be broken into smaller pie graphs with a different pie graph showing death type for each demographic (sex, ethnicity, age-group).
* Hovering over one demographic will highlight it in other visualizations.
* Hovering a point in time on the stacked line graph will show a breakdown of the demographics for those deaths, similar to the streamgraph example in the Effective Visualizations video.


## Unfinished Work

* Create menu for pie graph that will filter the current pie graph by demographic.
* Create breakdown of pie chart into smaller pie charts by demographics so there are multiple pie graphs
* Add hovering visualizations that align the stacked line graph to the pie graphs.
