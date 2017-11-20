# Robots
Creating a simple replica of the BSD/GNOME robots game in Python

Overview:
- Like the original, the player gets one move per turn, with each turn they stay alive equating to a point. They can move in any direction,
each turn, the robots in the play area move one 'block' towards the player, and, if they reach the player (on the same block) the player dies.
However, if the robots collide on a 'block' they are deleted and turned into a scrappile, which is a static filler on a 'block' which kills
anything on the same block.

Rules:
- You get one move per turn, as does each robot
- You may move north, north-east, east and so on (as do the robots)
- If a robot catches you, or you step on a junk pile, you die.
- If a robot runs into another robot, they die and turn into a junk pile.
- If a robot runs into a junk pile, it dies.

