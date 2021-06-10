# Answer the following questions:
["Image"](Image 6.1.3.png)
```
a. “Location of element in list” fails the disjointness property. Give an example that illustrates this:
    If the element is first entry in list, Block 1 and Block 2 will be jointed.
b. “Location of element in list” fails the completeness property. Give an example that illustrates this:
    If the element is last entry, it can either be null or not in the list.
c. Supply one or more new partitions that capture the intent of “Location of element in list” but do not suffer from completeness or disjointness problems:
    - Block 1: element is not null but it still in the list.
    - Block 2: element is either not null or not in the list.
    - Block 3: element is null.
```
