**Answer questions a–d for the graph defined by the following sets:<br>
N = {1, 2, 3}<br>
N0
= {1}<br>
Nf
= {3}<br>
E = {(1, 2), (1, 3), (2, 1), (2, 3), (3, 1)}
Also consider the following (candidate) paths:
p1 = [1, 2, 3, 1]<br>
p2 = [1, 3, 1, 2, 3]<br>
p3 = [1, 2, 3, 1, 2, 1, 3]<br>
p4 = [2, 3, 1, 3]<br>
p5 = [1, 2, 3, 2, 3]**

```
(a), Which of the listed paths are test paths? For any path that is not
a test path, explain why not.
  -The listed path which are not test paths is path number 5 (p5 = [1, 2, 3, 2, 3]) since p2 and p3 are test paths. p1 does not terminate at a final node. p4 does not
start at an initial node.
(b), List the eight test requirements for Edge-Pair Coverage (only the length two subpaths).  
  -The edge pairs are:
{ [1; 2; 1]; [1; 2; 3]; [1; 3; 1]; [2; 1; 2]; [2; 1; 3]; [2; 3; 1]; [3; 1; 2]; [3; 1; 3] }
(c) Does the set of test paths from part (a) above satisfy Edge-Pair Coverage? If not, state what is missing
  -No. Neither p2 nor p3 tours either of the following edge-pairs: { [2; 1; 2]; [3; 1; 3] }
(d) Consider the prime path [3; 1; 3] and path p3. Does p3 tour the prime path directly?With a sidetrip?  
  -p3 does not directly tour the prime path. However, p3 does tour the prime path with the sidetrip [1; 2; 1].
