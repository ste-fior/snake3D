**snake3D**

This interactive graphics project aims to implement a reproduction of the famous videogame “snake” in a new 3d version.
In order to implement this new version of the game, we decided to use the tools offered by the library ThreeJS. These instruments allow to build the scene as a big hierarchical tree. In fact, it is rooted with the main “scene” and then all the branches lead to a different object of the world: snake, background, lights, apple and ground.

The main challenge was to reproduce properly a natural and continuous motion for the snake.  Different geometrical shapes compose the snake, and we assembled them in order to create a realistic animal which slithers in the grass of the field. The synchronization among all these parts required a huge work which reported also some important problem that we had to solve. The most important of these problem was called “action reactivity”, and it was solved in order to manage correctly the interaction between the grid world, the snake and the user’s commands.

In addition to the snake, we implemented different objects which define and enriches the world where the user plays. A set of light sources was implemented: the most important are a moon and a sun which moves in a semi-naturalistic way and shines the scene. Then we defined three camera views which allow the user to interact with game by playing using different views.
In the end we added a set of music and effects in order to improve the entertaining aspect of the game.



The game can be played at: https://Fiorav.github.io/snake3D/snake.html

The code works properly on Firefox and Edge browsers.
