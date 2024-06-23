![image](https://github.com/Farhad0111/CSE-366-AI-TicTacTeo5x5/assets/109299643/b697590f-3247-4d35-aa05-a579fad63337)

CSE366: Game Based Assignment


Necessary Knowledge Required: Game Tree, Backtracking, State Saving in games, Alpha Beta Pruning. 


Team Formation: There will be at most three members in each group. More than that will not be allowed. 


Game 1: Tic Tac Toe 


  You need to implement the famous two player game Tic Tac Toe using your preferred language. Here the main change is that, the board of the game is not 3 x 3 but 5 x 5. A player wins if he can match his drawn symbols in consecutive three cells either vertically or horizontally or diagonally, the generic winning constraint of the traditional 3 x 3 tic tac toe game. 

  You will be given an initial configuration of the current status of the board including the human player’s last move. From that position, you need to make the game interactive between the PC and the human player by alternating their moves. Pc will give a move, then you will take input from the human player and again pc will give a move and so on. Pc will apply AI knowledge to pick up the move that will give him the best result.


![image](https://github.com/Farhad0111/CSE-366-AI-TicTacTeo5x5/assets/109299643/310ce73a-cd53-4127-b7d0-aca475076afc)


Report Criteria:


  During submission, you need to submit both the report and the code. From each group there will be one 
submission. You can choose any one of the following as the project to complete your task. The content of 
the report needs to following, 
  1. The problem statement 
  2. Formal algorithm writeup and discussion how the problem is approached 
  3. Conclusion that will state the challenges that you have faced and the topics that you have learnt 
  during implementing the idea. 



Problem Statement: 

  Implementing a 2-player game of Tic Tac Toe with a 5 x 5 board. The players will be a human and a computer. The goal is to match symbols in consecutive three cells either vertically or horizontally or diagonally. The computer will use AI to determine its moves.

  The game will start with a given initial configuration of the board, including the human player's last move. The game will alternate between the human player and the computer. The computer will make its move based on AI knowledge, and the human player will input their moves.

 The game will end when either a player matches their symbols in consecutive three cells or when the board is full. In the case of a full board without a winner, the game will end in a draw.

Discussion:

  This is a Tie Tac Teo game in which the user plays against an AI player. The game is represented by 5x5 board with X’s and O’s. The user always goes first as X, and the AI player always goes second as O. The first player to get three in a row, column, left diagonals, right diagonals win the game. If all the spaces on the board are filled and no player has three in a row, column, left diagonals and right diagonals, the game is a draw.

Conclusion:

  In conclusion we can say, the tic-tac-toe game is basically for two players. One player plays X and the other plays O. The players take turns placing their marks on a grid of five -by-five cells. If a given player gets three marks in a row horizontally, vertically, or diagonally, then that player wins the game. Tic Tac Toe can be used to promote several cognitive skills including counting and spatial skills, and color and shape identification. In order to make the game unbeatable, it was necessary to create an algorithm that could calculate all the possible moves available for the computer player and use some metric to determine the best possible move. After extensive research it became clear that the Minimax algorithm was right for the job.
