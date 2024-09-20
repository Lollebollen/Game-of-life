# Game-of-life
Made Conoway's Game of life in unity using a computeShader.

There are a few problems with my implementation, first due to not handling memory writing/reading properly sometimes cells read new changes in the same generation.
Secondly since my way of handeling the index of each buffer is done improperly i get inconsistente behavior depending on which side of the grid a call takes place.
Lasty there is a memory leak which i have not yet found.

I could also improve performance furter by not making a new sprite each tick and instead use a pixel shader to make a material.
