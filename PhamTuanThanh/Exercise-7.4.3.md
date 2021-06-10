# Use the following program fragment for questions a–e below:
![image](https://user-images.githubusercontent.com/74814233/121546248-58fd3a00-ca35-11eb-8f13-3e8e4935cd7c.png)
**Use the following test inputs:
t1 = f1 (0, 0)<br>
t2 = f1 (1, 1)<br>
t3 = f1 (0, 1)<br>
t4 = f1 (3, 2)<br>
t5 = f1 (3, 4)<br>
(a) Draw the call graph for this program fragment.<br>
(b) Give the path in the graph followed by each test.<br>
(c) Find a minimal test set that achieves Node Coverage.<br>
(d) Find a minimal test set that achieves Edge Coverage.<br>
(e) Give the prime paths in the graph. Which prime path is not
covered by any of the tests above?**


## a, Draw the call graph for this program fragment.
The code shows (2) is final and (6) may be final, nodes (1), (3), (4), (5) are not final. 
  Graph:
![image](https://user-images.githubusercontent.com/74814233/121547308-3a4b7300-ca36-11eb-86c9-fd6b2911e577.png)

## b, Give the path in the graph followed by each test
  • t1: [f1, f3, f5, f6]<br>
  • t2: [f1, f3, f4, f6]<br>
  • t3: [f1, f2]<br>
  • t4: [f1, f3, f4, f6]<br>
  • t5: [f1, f2, f3, f4, f6]<br>
  
## c,  Find a minimal test set that achieves Node Coverage.  
  Three possibilities: {t1; t2; t3}, {t1; t3; t4g}, or {t1; t5}.

## d, Find a minimal test set that achieves Edge Coverage.
  One possibility: {t1; t5}
  
## e, Give the prime paths in the graph. Which prime path is not covered by any of the tests above?
  There are 4 prime paths: { [f1, f2, f3, f4, f6], [f1, f2, f3, f5, f6], [f1,f3, f4, f6], [f1, f3, f5, f6] }. The second of these paths is not covered by the given test paths.
