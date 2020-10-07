# Data Visualization Project

## Data

This data shows the number of deaths by suicide, firearms, and alcohol based on age group, race, and sex.

Source:
Data World
[Suicide Deaths by Age, Race, and Sex](https://data.world/healthdatany/j6fz-a4ta/workspace/file?filename=vital-statistics-suicide-deaths-by-age-group-race-ethnicity-resident-county-region-and-gender-beginn-1.csv)


## Prototypes

I’ve created a proof of concept visualization of this data. It's a bar graph and it shows the number of firearm deaths over time, split among sex.

[<img width="956" alt="Screen Shot 2020-09-30 at 12 13 58 AM" src="https://user-images.githubusercontent.com/23406389/94642389-f783a980-02b1-11eb-8d6a-afa3d0f93256.png">](https://vizhub.com/PeterMaidaRobot/35ffbebba3f14ef295ee210de4d77c15)

I've also created a stacked bar/"line" graph that shows the numbers of deaths over time broken down by each cause.

[<img width="954" alt="Screen Shot 2020-09-30 at 12 14 10 AM" src="https://user-images.githubusercontent.com/23406389/94642413-0702f280-02b2-11eb-82e4-52aefb5ddc88.png">](https://vizhub.com/PeterMaidaRobot/a262ae234afd4ab59cae693467e000c4)


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


## Open Questions

I am unsure of the most interesting and efficient way to describe all of this data at once.


## Interactions Ideas

Potential interactions can include:
* A menu on the stacked line chart to filter by the different types of (suicide, firearm, alcohol).
* One pie graph that can be broken into smaller pie graphs with a different pie graph showing death type for each demographic (sex, ethnicity, age-group).
* Hovering over one demographic will highlight it in other visualizations.
* Hovering a point in time on the stacked line graph will show a breakdown of the demographics for those deaths, similar to the streamgraph example in the Effective Visualizations video.


## Schedule of Deliverables

* Create stacked line graph for the number of deaths on the y axis and time on the x axis. Stacked lines will be type of death. (4 hours, 10/12)
* Create menu for stacked line graph that filters out different types of deaths. (2 hours, 10/16)
* Create menu for stacked line graph that filters out different types of demographics (sex, ethnicity, age-group). (3 hours, 10/20)
* Create pie graph of the data. (2 hours, 10/24)
* Create menu for pie graph that will filter the current pie graph by demographic. (2 hours, 10/26)
* Create breakdown of pie chart into smaller pie charts by demographics so there are multiple pie graphs. (6 hours, 10/26)
* Add hovering visualizations that align the stacked line graph to the pie graphs. (4 hours, 10/30)

Note times are rough, I have little knowledge on how difficult working with D3 and React might be.
