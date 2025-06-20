# CSCI-5654-Assignment-5-Reading-Slides-on-ILP-Vanderbei-Chapter-23-solution

Download Here: [CSCI 5654 Assignment #5 (Reading: Slides on ILP, Vanderbei Chapter 23) solution](https://jarviscodinghub.com/assignment/assignment-5-reading-slides-on-ilp-vanderbei-chapter-23-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

P1. (10 points) Solve each of the problems below using a branch-and-bound method. Write
down the solution obtained and the enumeration tree obtained. You may use any LP solver of your
choice to solve the subproblems. Please do not use a ILP solver directly.
(A)
max 2×1 −3×2 −2×3 −x4
s.t. x1 −x2 +x3 ≤ 5
x1 −2×2 −x3 +x4 ≤ 3
x1 −x2 −x3 −x4 ≤ −1
x1, x2, x3, x4 ∈ [−5, 5]
x1, x2, x3, x4 ∈ Z
Hint: Use x4 as the variable to branch on.
(B)
max 2×1 +3×3 +x4
s.t. x1 −x2 +x4 ≤ 1
2×2 −x4 ≤ 2
x1 −x3 −2×4 ≤ −1
−x1 +x4 ≤ 1
x1 ∈ {−2, −1, 0, 1, 2}
x2 ∈ {−1, 0, 1}
x3 ∈ {0, 1}
x4 ∈ {−1, 0, 1}
P2. (10 points) Consider the final dictionaries for the LP relaxation of a few ILPs. Assuming all
variables are integers, write down all the cutting planes:
Dictionary # 1:
x1 0.666666666667 −0.666667×5 +0.333333×4
x2 1 −1×5
x3 2 +4×5 −1×4
z 1 −1×5
Dictionary # 2:
x4 4.33333333333 +0.333333×8 +0.666667×9 −0.333333×3
x5 8.66666666667 −0.333333×8 +0.333333×9 −2.666667×3
x6 10 −1×3
x7 3 −3×8 +1×9 −18×3
x1 5.66666666667 −0.333333×8 −0.666667×9 +0.333333×3
x2 1.33333333333 +0.333333×8 −0.333333×9 +2.666667×3
z 7 −1×9 −2×3
1
P3 (20 points). Consider the graph below which shows various locations and the driving times
between them in hours:
Our goal is to decide whether or not to place a hospital at each node. The following are the
cost of building a hospital at various nodes in millions of dollars:
Node Cost
1 3
2 3
3 1.5
4 1
5 1.2
6 1.3
7 0.9
8 0.8
The following constraints should apply to our placement of hospitals: each node should either
have a hospital or be within 1 hour driving distance of a hospital.
For your convenience, the table of pairwise shortest path distances is given as an excel spreadsheet.
(A) Let G be a graph with n nodes and W(i, j) denote the shortest path weight between nodes i
and j. Finally let c be a n × 1 vector of node costs. Write down an integer linear programming
formulation of the above problem.
(B) Formulate and solve your ILP for the given example.
P4 (15 points) Consider a polyhedron P given by the constraints
Ax ≤ b, ` ≤ x ≤ u .
(a) Write down mixed integer programs that will find the point x ∈ P with the largest number of
0 entries in x,
(b) Write down mixed integer programs that will find the point x ∈ P with the smallest number
of 0 entries in x.
2
(c) Write down a mixed integer program that will search for a solution x ∈ P maximizing an
objective function c
tx such that x does not satisfy a ≤ x ≤ b, for given a, b.
P5 (10 points) We are given sets of numbers hS1, . . . , Ski such that each Si ⊆ {1, . . . , n}. For
example, n = 10 and the sets are
S1 : {1, 3, 6}, S2 : {2, 7, 8}, S3 : {1, 8, 9}, S4 : {1, 6, 5, 3} .
Our goal is to select a subset S ⊆ {1, 2, . . . , n} such that S ∩ Si 6= ∅ for i = 1, . . . , k and the
sum of elements in the chosen set S is minimized.
Formulate a 0−1 ILP for the problem for given n, k,hS1, . . . , Ski. Also, solve it for the example
above.

