# Programming-Assignment--1
A set is a collection of items without repetitions. The goal of this assignment is to implement a set as a data structure. Do the following.

1. (30 points) Starting with the template attached, implement a generic
class SethTi that maintains a set of items of generic type T using the
class ArrayListhTi in the Java API. Your Set class must provide the
following instance methods:
    - **add**: that adds a new item. (Ignore if already in the set.)
    - **remove**: that removes an item. (Ignore if not in the set.)
    - **membership**: that returns true if a given item is in the set and
    false otherwise.
    - **toString**: that returns a string with the list of the items in the
    set.

2. (30 points) Write a testSet class with a main() method that tests
all the operations of the Set class above. That is, create an empty
set A of integers, obtain from the user some integers and store some
in A, display the set using toString(), obtain from the user some
integers and remove them from A using remove(), display the set using
toString(), obtain an integer from the user and check whether it is in
A or not using membership() and display the result.

3. (20 points) Fill the following table with the big-O running times of
each of the methods implemented, as well as the running times for the
same methods if they were implemented with LinkedList instead. (No
need to explain here, only the big-O expression.)

4. (20 points) Explain each of the eight running times in the table applying the rules of counting seen in class, and for the method calls, if we have covered them already, directly refer to the running times of
those methods.
   - (Partial credit if you do not explain all eight. No points for ambiguous
      explanations. For instance, if you implement add in the class Set using
      addFirst in the class ArrayList, then you should say something like
      the following. “The add method of Set is implemented with just one
      method call to addFirst of ArrayList. addFirst of ArrayList is in
      O(n) in the worst case. Hence, the same bound on the running time
      applies to add”. )

5. (Extra credit) Expand your class SethTi with the following static methods, and expand your testSet class to test them.
    - **union**: that returns the union of two given sets.
    - **intersection**: that returns the intersection of two given sets.
    - **difference**: that returns the difference between two given sets

