# top-down-game
a simple, WASD-control top-down game experiment with pure html and javascript

it is scaled up 2x for visibility, but based on gameboy games which use 16x16 overworld sprites.

no collision detection, objects events or anything. 

just working on reliable pixel-perfect movement for now. ensures that the sprite moves 32 pixels for each WASD - no more, no less.

press spacebar at any time to update debug values, they update automatically while moving around.

getting the sprite to move fluidly with 32 frames of motion, one for each pixel... without overshooting... using `setInterval`.... was really annoying. there are still glitches, mainly weird peculiarities of how javascript handles keyboard events it seems like.

tried making a walking animation work but `setInterval` and `clearinterval` are still confusing to me as im not very familiar with them.

eventually will add object and collision layers probably just a csv that is loaded with the level and moves with the map and sort out a better animation system.
