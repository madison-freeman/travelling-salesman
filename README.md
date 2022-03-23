# Travelling Salesman Problem
Sorted a doubly linked list of size N using quicksort. 
Created a function partition(), which accepts the first and last node of the given linked list as input parameters and returns the pivot's address. 
* Expected Time Complexity: O(2n * n2)
* Expected Space Complexity: O(2n * n)
* Constraints: 1 <= n <= 10, 1 <= cost[i][j] <= 103

## Table of Contents

1. [Overview](#overview)
3. [Project Motivation](#project-motivation)
4. [Solution](#solution)
5. [Author](#author)

# Overview <a name="overview"></a>
Given a matrix cost of size n where cost[i][j] denotes the cost of moving from city i to city j. Our task is to complete a tour from the city 0 (0 based index) to all other cities such that you visit each city atmost once and then at the end come back to city 0 in min cost.

# Project Motivation <a name="project-motivation"></a>
The travelling salesman problem (TSP) asks the following question:"Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?" It is an NP-hard problem in combinatorial optimization, important in theoretical computer science and operations research. The salesman's goal is to keep both the travel costs and the distance traveled as low as possible. Focused on optimization, TSP is often used in computer science and computational mathematics to find the most efficient route for data to travel between various nodes. Applications include identifying network or hardware optimization methods. However, current methods require each instance to be solved individually. A general solution has eluded mathematicians for decades. This difficulty is due to the fact that the TSP is an NP-hard problem. This means that, among other things, the TSP is a problem in which correct solutions are easy to verify, but there is no efficient way to solve the problem itself. This also means that a solution to the TSP would put to rest the question of whether or not it is possible to solve NP-complete problems. Called the P versus NP problem, this is one of the most challenging questions facing mathematicians today. In fact, it was designated a millennium prize problem by the Clay Mathematics Institute. This means that the one who solves this problem will win a million dollar prize.

## Author<a name="author"></a>
* [Madison F.](https://github.com/madison-freeman)
