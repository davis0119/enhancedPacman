Inheritance/Subtyping
  
I had a main Ghost class with a couple of abstract methods. Each 
type of ghost extended this class and handled lasers and attacks differently. 
The red ghost hurts the play 3x as much as walls. The cyan ghost reflects lasers and
eats all of the laser juice that the use collected. The orange ghost
saps laserfuel and health. The pink ghost hurts the player to the 
brink of death but gives them a lot of fuel.

=========================
=: Overview :=
=========================

The Player class constructs a yellow square (Squareman) 
that can be controlled with arrow keys. The player can get hurt by walls
constructed by the wall class. The goal is to collect all the laserfuel,
but it could be fun to shoot at walls and lasers.

The Ghost class is an abstract class that is a superclass for different types
of ghosts, which are enemies with all different types of abilities. 

Again, the red ghost hurts the play 3x as much as walls. The cyan ghost reflects lasers and
eats all of the laser juice that the use collected. The orange ghost
saps laserfuel and health. The pink ghost hurts the player to the 
brink of death but gives them a lot of fuel.

The LaserFuel class and Laser class both extend the GameObj class to detect
collisions. 

========================
=: External Resources :=
========================

  I just used some sprite images for the ghosts found on Google Images.
  Else I just used Javadocs to figure out rectangles.
