# Exercise 3.5
## Find the flaw and describe it in terms of the RIPR model. 
```Java
@Test
public void testSort()
{
  names.add("Laura");
  names.add("Han");
  names.add("Alex");
  names.add("Ashley");
  names.sort();
  assertTrue("Sort method", names.getFirst().equals ("Alex"));
}
```

This assertion only check for the first element.

RIRP model:
* Reachable: if the error in the first element is passed, if for the other elements, it is not..
* Infection: yes
* Propagation: no, the whole list can be false but the first element can still be true.
* Reveal: no, the test assertion cannot reveal the error.
