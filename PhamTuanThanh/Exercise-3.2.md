 # Give a one or two paragraph explanation for how the inheritance hierarchy can affect controllability and observability
 

Inheritance hierarchy use Object-oriented concepts and having an inheritance tree of classes
that could be become more complex to test, since the sub classes are dependent of its father,
which means that every test affected by the changes must be updated for the sub classes.

As a result, controllability is affected as we will need to control every super class and its sub classes, 
which will be highly hard if we have a deep inheritance tree.
On the other hand, it has an impact on observability because we must monitor a huge number of subclasses that do the same tasks as the superclass.
