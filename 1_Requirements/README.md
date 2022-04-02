# Requirements
# Introduction
This is a simple game of tic tac toe . Most of the games I have seen online require two players, and I wanted to try creating a game where one player plays against the computer.
# Rules of the Game
- 1.The game is to be played between two people .
- 2.One of the player chooses ‘O’ and the other ‘X’ to mark their respective cells.
- 3.The game starts with one of the players and the game ends when one of the players has one whole row/ column/ diagonal filled with his/her respective character (‘O’ or ‘X’).
- 4.If no one wins, then the game is said to be draw.

# Features
The game is played on a grid that's 3 squares by 3 squares. You are X, your friend (or the computer in this case) is O. Players take turns putting their marks in empty squares. The first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner. When all 9 squares are full, the game is over.

# Why:
It is a fun game. easy to undusted and play.
it is a good exercise of c programming it simply helping you to learn skills projects allow you to produce something .
# Where:
It can be used in our laptops or desktops.
# Who:
It can be used by anyone who understand the rules of this game.
But two players are the limit for this game.
# When:
It Can be used as timepass game like when you bored and you wants to put your time in Logical games you can go for this

# How:
Can be operated from Personal computer or laptop.

## Strength:
Perfect for basic programming exercises at initial stage of your learning process .
## Weakness:
GUI is not so attractive.
keyboard is only activated in the game.
## High Level Requirements
|  ID	 | Description	                                  |Status      |
|------|------------------------------------------------|------------|
|HLR1  | The user can change its selected sign("0","x")	|Implemented |
|HLR2  |	User will be able to choose 'O' to play       |Implemented |
|HLR3  |	One of the User will lose	                    |Implemented |
|HLR4  |	One of the User will win                	    |Implemented |
|HLR5  |	Game may end up in a Draw situation	          |Implemented |

## Low Level Reuirements
|ID	    | Description	                 | Status      |
|-------|------------------------------|-------------|
|LLR1	  |If the user presses '1',then the game is started |Implemented |
|LLR2	  |If the user presses '2’,then  the LeaderBoard will be dispalyed |Implemented |
|LLR3	  |Asks to enter the name of the player1	|Implemented |
|LLR4	  |Asks to enter the name of the player2	|Implemented |
|LLR5	  |If the Player1 is playing with 'X', then Player2 gets’O’	|Implemented |
|LLR6   |If the player1 gets 3 Xs or 3 Os in vertical,horizontal or diagonal row, User will lose	|Implemented |
|LLR7	  |If the player2 gets 3 Xs or 3 Os(as per his choice), in vertical,horizontal or diagonal row, he'll win	|Implemented |
|LLR8   |If the total number of moves, i.e., 9 moves have been completed and neithe the player1 nor the player2 has won, it'll end up in a draw	|Implemented |
