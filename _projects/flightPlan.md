---
layout: page
title: Flight Planner
permalink: /flightPlan/
---
# Flight Planner

Using an adjacency list of flight paths and iterative backtracking, this project will display the fastest or cheapest flight paths from a wanted origin to a wanted destination. 

![Flight Chart](/assets/flightMap.png) 

First, I created a <a href="https://github.com/leongkkevin/flightPlanner/blob/master/Flight.h">Flight object</a> that holds the origin, destination, cost, duration, and airline of the flight. Then, I parsed through the flight path input file and added flights to a <a href="https://github.com/leongkkevin/flightPlanner/blob/master/FlightAdjList.h">flight adjacency list object</a>. This adjacency list would hold all the possible flight paths between each city.

Next, I parse in the user input file of wanted flights. Using iterative backtracking and a self-made <a href="https://github.com/leongkkevin/flightPlanner/blob/master/DSStack.h">templated stack object</a>, the algorithm searches through the entire adjacency list and stores all flight paths from a wanted origin to a wanted destination in another adjacency list.
<br><br>
*An example of a flight data and wanted flights is shown below:*
![Flight Info](/assets/flightInfo.png)
<br>
The algorithm then iterates through the saved flights adjacency list and records the total cost and time for each flight path - adding 43 minutes and $19 to the time and cost for each layover.
The algorithm then sorts the list by either time or cost (represented in the input file by a "T" or "C" respectively) and prints the 3 fastest or cheapest flight paths from the wanted origin to the wanted destination.
<br><br>
*An example output using the inputs above is shown below:*
![Flight Output](/assets/flightOutput.png)

Happy travels!

<a href="https://github.com/leongkkevin/flightPlanner">*Click here for the full Github Repository*</a>