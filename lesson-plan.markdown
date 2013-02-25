The Travelling Saleswoman
=========================

Materials
---------

- A couple of packs of Post-it Notes (at least two colours)
- String, cut up into varying strips of length (between 10cm and maybe 2m)
    - Lengths of string should be have number labels stapled to them
      proportional to their length.
    - Make sure the numbers are sufficiently large that you can't add them up
      in your head
- A calculator
- (Maybe) a toy car (?)
- At least 5 children, at most 20

Plan
----

1. Get a few children (5) to hold a few of the lengths of string.
   Take care to ensure that not all children are connected and that
   there is some variation in the lengths of string

2. Pick two children and get them to work out the shortest route
   between them.  Do not use any special algorithm at this point, just
   make sure that everyone gets the idea.

3. Add a few more children and lengths of string to the graph so that
   it's slightly hard to work out the shortest path.

4. Talk about different methods of finding the shortest route.
   Discuss ways of doing this including:
   	- Trying out every path
	- Trying out random paths

5. Talk about wanting to find the shortest route as quickly as
   possible.  Discuss how long it would take to try every possible
   path.  Discuss what the chances are that doing some random routes
   gets you the shortest route.

6. Introduce a new method for finding the shortest route
       1. Begin at the starting child and give him the yellow label "0"
       2. Label all the children that are connected to the current child with
       	  the length of the string summed with the current child's label
       3. Label this child with a pink label.  This means he has been visited
       4. If this was the ending child, stop
       5. Move to an unvisted child and go to step 2

7. Try this method out a few times so that everyone is familiar with
   it.

8. Discuss how much slower this method gets as you add more children.
   Talk about adding a child that doesn't have much string vs one that
   does have a lot of string.  Help them to come to the conclusion
   that if you double the number of children, it normally can take
   more than twice as long.

7. New problem.  Jenny is a travelling saleswoman.  She is not trying
   to find the shortest path between two places.  She wants to visit
   every place and then return home in the shortest possible way.

8. Tell them that there is no method for doing this, and that you
   really do have to try every possible path.  Discuss how much longer
   it takes when you increase the number of children.  Help them to come
   to conclusion that this problem gets really hard really fast - much
   harder than finding the shortest path.