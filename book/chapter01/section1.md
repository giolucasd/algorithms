# 1.1 Algorithms

## Notes

No notes yet.

## Exercises

### 1.1-1

**Describe your own real-world example that requires sorting. Describe one that requires finding the shortest distance between two points.**

An example of real-world task that requires sorting is exhibiting NBA standing, with teams ordered by their numbers of victories in the regular season.

An example of real-world problem that required finding the shortest distance between two points is planning the route for a trip, with multiple tourist stops. We could, for example imagine that a traveler wants to spend the minimum amount of money in the trip and model the problem with a graph in which nodes are tourist stops and edges represent the price to travel from one node to another using a particular transport. The same could be applied if the traveler wanted to spend the minimum amount of time on the road and we used edges to represent the time spent between two nodes using a particular transport.

### 1.1-2

**Other than speed, what other measures of efficiency might you need to consider in a real-world setting?**

On a purely algorithm analysis, the most common measures of efficiency are speed and memory usage.

In a real-world scenario, taking hardware tradeoffs at account, power consumption, bandwidth, hardware costs, algorithm development or maintenance costs and other business criterias might be more relevant.

### 1.1-3

**Select a data structure that you have seen, and discuss its strenghts and limitations.**

A data structure that I've seen is an array. The biggest strenght of an array is that access to any element takes O(1) time, allowing great randomized access time. Its biggest limitation, although, is that insertion and removal of elements might be very costly.

### 1.1-4

**How are the shortest-path and traveling-salersperson problems given above similar? How are they different?**

Both problems are similar in the sense that they can be modeled using graphs and the objective in to minimize distance. They are different, because in the shortest-path problem the objective is to minimize the distance from a vertex to another, whilst in the traveling-salesperson problem the objective is to minimize the distance for a graph circuit, starting in a vertex and visiting a set of others. Note that not necessarily the minimum distance circuit would take the shortest-path between two vertices in the path.

### 1.1-5

**Suggest a real-world problem in which only the best solution will do. Then come up with one in which "approximately" the best solution is good enough.**

An example of real-world problem in which only the best solution will do is sorting swimming athletes by battery time. An "approximately" ordered list of the athletes would not grant that the correct athletes would be selected.

Finding a route from one place to another, although, is a problem in which "approximately" the best solution will do, since one could use a suboptimal route and still get to their destiny.

### 1.1-6

**Describe a real-world problem in which sometimes the entire input is available before you need to solve the problem, but other times the input is not entirely available in advance and arrives over time.**

I can't think of one right now. Maybe online game character animation depending on network information.