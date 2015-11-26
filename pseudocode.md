#Algorithm for A.I board placement
Define a 10x10 boolean array with x and y coordinates.
Define the aircraft carrier, battleship, cruiser, submarine, and destroyer (5, 4, 2, 3, 3)
Repeat until all ships are placed:
{
Pick 2 random numbers and use that as the coordinates for ship. If it's not valid, try again.
Pick a random orientation (up,down,left,right)
Pick a random ship out of the predefined ones.
Randomly determine an orientation and place it on. If it's not valid (conflicts with board edges or another ship), repeat until it is.
}

#Algorithm for Human board placement
Define a 10x10 boolean array with x and y coordinates.
Define the aircraft carrier, battleship, cruiser, submarine, and destroyer
TODO

#Game vs. Human Algorithm
Repeat until someone loses:
{
17 valid pegs.
One person makes clicks on a grid. If it's a hit, reduce the user's valid pegs left and turn cell into red, if not, turn cell into white. 
Check if someone has lost (0 pegs left). If not, other player's move.
}

#Game vs. AI Algorithm
Repeat until someone loses:
{
Refer to Game vs. Human Algorithm
A.I turn:
Define a last hit coordinate.
If there is no previous last hit coordinate, pick a random coordinate as a shot. If there is a previous last hit, pick a random adjacent block.
Display to user where and whether it hits or not.
If it hits, set the last hit coordinate to the hit coordinate.
}

#Network
TODO

Example: http://en.battleship-game.org/