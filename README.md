# Dijkstra-Indian-Cities
Implementation of Dijkstra's algorithm to find shortest road distances between Indian cities.
The shortest road distance between Indian Cities using Dijkstra's algorithm.Shortest Road Distance Between Indian Cities using Dijkstra's algorithm

## Objective

This project aims to implement Dijkstra's algorithm to calculate the shortest road distance between cities in India.

There's a weighted graph with nodes representing each city, with the weight on each edge being the distance of the road between the two cities.

## Dataset

The data set for the project is an open-source data set with 50 Indian cities and distances.

The dataset contains:

In the spreadsheet Distances.csv, you will find the distance between the cities.
- Population_2010.csv – population of cities (2010).

Dataset source:

https://github.com/nikhil-likhar/Cities-Dataset

## Algorithm Used

### Dijkstra's Algorithm

Dijkstra's algorithm is an algorithm used for finding the shortest path from a starting city to every other city in a weighted graph, where the weights on the edges are non-negative.

The algorithm is as follows:

 1. Set the distance of the source city to 0.

2. Make the distance of all other cities become infinite.

3. Pick the unvisited city that is closest to the square.

4. Examine all neighbouring cities.

5. If a shorter distance is found, update the distance.

6. Repeat until all the reachable cities have been processed (Step 6).

7. Save the last city to draw the shortest path again.

## Implementation

The algorithm was implemented in Python.

In order to make the selection of the city with the minimum temporary distance efficient, we use a priority queue implemented with the Python standard library module, heapq.

The project also reconstructs the complete shortest route between the source and destination cities.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- GitHub

## Example

As an example for the Delhi city, the shortest road distance from Delhi to all other cities in the program is calculated.

The program also prints the shortest path associated with it.

## Complexity

Using a binary heap priority queue:

**Time Complexity:**

O((V + E) log V)

**Space Complexity:**

O(V + E)

where:

- V = number of cities
Any number consist of 1, 2, or 3 digits.Any number is made up of digits from 1 to 3.

## Visualization

Shortest route between cities shown in a plot using the latitude and longitude dataset.

## Conclusion

Dijkstra's algorithm has been successfully used to perform the computation of the shortest road distance from one city to another in India.

Implementation shows how to program a road network using a weighted graph and the use of Dijkstra's algorithm to find the minimum cost path.
