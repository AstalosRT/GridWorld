Part 1:
1. No, it only moves if the cell is empty or if there is a flower.
2. It tries to move forward.
3. It turns 45 degrees to the right until it can move.
4. A bug leaves a flower in the cell it leaves.
5. If a bug is told to act on the edge, it turns 45 degrees, and will turn 45 degrees again if told to act again.
6. A bug wil turn if there is a rock in front of it.
7. No, a flower doesn't move.
8. A flower gets darker over itme until it is gray.
9. A rock does not move and does not have any other behaviors.
10. A location in the grid can only have one thing in it at a time.
Part 2:
1. the sideLength instance variable defines the number of steps a bug moves on each side of the box.
2. The steps instance variable keeps track of how many steps a bug has moved on each side of the box.
3. When a bug moves sideLength steps, it has to turn 90 degrees to be able to move along the next side.
4. The BoxBug class extends the Bug class, and the Bug class has a move function, so the BoxBug class can call that function and move.
5. Yes. The side length can not be changed.
6. Yes. If a rock or another bug is in front of it, it will change its path.
7. The steps value it set to zero when a bug is constructed.
Part 3:
1. locl.getRow()
2. false
3. (4,4)
4. 135 degrees
5. It finds the adjacent neighbor and returns a value in degrees.
a. Turn
b. Turn
c. Turn
d. Turn, remove actor from grid
e. Trun, remove jumper from grid
f. What if the jumper is surrounded by other actors on the grid
a. Extend the Bug class. Jumper states that it is an actor, so it extends Actor.
Part 4:
1. act, getActors, processActors, getMoveLocations, selectMoveLocations, makeMove
2. getActors, processActors, getMoveLocations, selectMoveLocations, makeMove
3. If it selects its actors from different locations than the Critter class, then it will need to override it.
4. It could make them move, change colors, or if circumstances were dire, it could eat all of them.
5. getMoveLocations returns the spaces that the critter can move to, and selectMoveLocations returns where the critter will move to, and if it can make a move, then makeMove moves the critter.
6. Critter extends Actor, and uses Actor's constructors; therefore, not needing its own.
