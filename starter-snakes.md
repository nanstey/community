Starter Snakes
=======

There are a host of [starter snakes](https://github.com/battlesnakeio?utf8=%E2%9C%93&q=starter-snake&type=&language=) to 
help you to get started building your first snake to compete in the Battlesnake tournament.

Each of the starter snakes have have enough scaffolding code to run a snake both locally and on heroku.
Every snake that takes part in Battlesnake is an http server that will accept requests from the battlesnake engine.

Snakes has three ways of interacting with the engine.

 - `start` - A call from the engine to tell the snake a game has begun.
 - `move` - A call from the engine to tell the snake the current board state and request the next move.
 - `end` - A cal from the engine to tell the snake that the game has completed. 
 
Each starter snake (should) also have three unit tests that you can run to ensure that these methods/functions are working.
