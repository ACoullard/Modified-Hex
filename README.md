# Modified-Hex

**Code available upon request**

A player for a modified version of the "hex" game. In the classic hex game, two players attempt to be the first to create a path from one side to the other of a board of hexagonal pieces.
In this modified version, the winner of the game is the player with the most "islands" of their color present on the board when a path from one side to the other is created - an island being any contiguous group of tiles of a single color.

# Features

* Play a modified version of the "hex" game
  * Place tiles in a intuative GUI and see real time updates of score and game state.
  * Play against another human player or a variety of AI opponents, on a variety of board sizes.
  * Pit two AIs agains eachother to compare their speed or effectiveness. See their game play out in real time.
  * See helpful diagnostic imformation on the speed of different algorithms on the boards. Test the available AIs or create your own new algorithms!
* AI Opponents:
  * Minimax - An implementation of the basic minimax algorithm
  * RandomMax - A modified version of the minimax algorithm that assumes random moves from the opposition
  * CachingMinimax - An implementation of minimax that caches results as the game goes on. Play against it on larger boards to see a speed improvement!
  * Alpha-Beta - An implementation of the minimax algorithm with caching and alpha-beta pruning. Play against it on larger boards to see a large speed improvement!

  

https://github.com/user-attachments/assets/c697f57f-9711-46f5-8103-1ec77353edd9

<div align="center"> 
  
  _Example of a game played against an AI opponent_
  
</div>

https://github.com/user-attachments/assets/5b130a06-7c77-4bac-ad4e-20f777ba8bcc
<div align="center"> 
  
  _Example of two AIs competing against one another_

</div>
  
