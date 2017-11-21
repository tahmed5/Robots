# Robots
Creating a simple replica of the BSD/GNOME robots game in Python

Overview:
- Like the original, the player gets one move per turn, with each turn they stay alive equating to a point. They can move in any direction,
and, each turn, the robots in the play area move one 'tile' towards the player. If they reach the player (when they are on the same tile) , the player dies.
However, if the robots collide on a 'tile' they are both deleted and turned into a scrappile, a static filler which kills
anything on the same tile. The playboard should be a large area, with sides that either join to the other side (such as in pac man) or are essentailly walls (we need to decide this).

Rules:
- You get one move per turn, as does each robot
- You may move north, north-east, east and so on (as do the robots)
- If a robot catches you, or you step on a junk pile, you die.
- If a robot runs into another robot, they die and turn into a junk pile.
- If a robot runs into a junk pile, it dies.

Coding Rules (to be decided):
- All functions/methods should be as modular as possible (not relying heavily on other functions)
- All variables should be pre-declared at the top of the method/function for readability
- All variables should have names directly relating to their use, this prevents same named variables (example: pathfindLoop1)
- All code should be explained by comments
- All code should be named and dated when changed or created (until the final version)
