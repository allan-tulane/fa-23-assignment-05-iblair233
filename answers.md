# CMPS 2200 Assignment 5
## Answers

**Name:** Izzy Blair






- **1a.**
If there are d branching paths on the d-ary tree, the height is log_d(n) where n is node amount.

- **1b.**
Both delete and insert are O(log d n)

- **1c.**
Work is O(e * log(d(e))) when changing from binary to d-ary
- **1d.**
d = 1

- **2a.**
Pairs: APSP(0,0,0)= 0 APSP(0,0,1)= 0 APSP(0,0,2)= 0 APSP(1,1,0)= 0 APSP(1,1,1)= 0 APSP(1,1,2)= 0 APSP(2,2,0)= inf APSP(2,2,1)= inf APSP(2,2,2)= 0 APSP(0,1,0)= inf APSP(0,1,1)= -2 APSP(0,1,2)= -2 APSP(0,2,0)= inf APSP(0,2,1)= inf APSP(0,2,2)= inf APSP(1,2,0)= inf APSP(1,2,1)= inf APSP(1,2,2)= 0

- **2b.**
Yes in this graph k of 1 and 2 are the same, because the three nodes are used once. Yes, you can write all APSP(i,j,2) in terms of APSP(i,j,1), because with one node in between start and destination, you can't return to previously visited nodes and there are only three nodes.

- **2c.**
The shortest path is vertices 0 through k-1 or i-k. The shortest path would be from k-j using 0 and k vertices.
- **2d.**
Work is O(dd!log_d(n)).
- **2e.**
Johnson's algorithm work will be better than ours for every circumstance.


- **3a.**
No, as the min spanning tree decreases weight, and MMET minimizes every possible edge. The MMET will always take the shortest edge between routes, which could increase overall tree weight..

- **3b.**
THe first and second best MST will have a difference of one edge, so we can calculate the best one by going by the second best MST.

- **3c.**
Final work is O(VElogE)
