# INTRODUCTION
Tic-Tac-Toe game is very popular and is fairly simple by itself. It is a computer based game for two players X and O. They take turns marking the spaces in the 3 x 3 grid with X and O alternatively. The player who succeeds in placing three successive marks either in horizontal, diagonal or vertical wins the game.
## RESEARCH
It is often used as a pedagogical tool for teaching the concepts of good sportsmanship and the branch of artificial intelligence that deals with the searching of game trees. It is straightforward to write a computer program to play tic-tac-toe perfectly or to enumerate the 765 essentially different positions (the state space complexity) or the 26,830 possible games up to rotations and reflections (the game tree complexity) on this space. If played optimally by both players, the game always ends in a draw, making tic-tac-toe a futile game.
## Cost and Features and Timeline
|Time  | 	Feature 	| Cost | 
|------|------------|------| 
|1558 |Started as a pen and paper game in Roman Emire, earlier it was called tic tac |Free (Pen and Paper)| 
|1952 |In 1952, OXO (or Noughts and Crosses), developed by British computer scientist Sandy Douglas for the EDSAC computer at the University of Cambridge, became one of the first known video games.|	$5 | 
|2000-2021 | 	After Digitalisation, this game is almost free for everyone on multiple mediums. It is played by anyone at anytime | Cost-efective |

## Rules of the Game
- The game is to be played between two people 
- One of the player chooses ‘O’ and the other ‘X’ to mark their respective cells.
- The game starts with one of the players and the game ends when one of the players has one whole row/ column/ diagonal filled with his/her respective character (‘O’ or ‘X’).
- If no one wins, then the game is said to be draw.
 
## Behavioral Diagrams:
### Use Case Diagrams:
![image](https://user-images.githubusercontent.com/75977407/161402084-fce04d4c-f18c-4d86-bf40-fa51f98dc239.png)
### Activity Diagrams:
 ![image](https://user-images.githubusercontent.com/75977407/161402086-eddaa873-6a5d-4314-902e-8398d2925436.png)
### Structural Diagram:
 ![image](https://user-images.githubusercontent.com/75977407/161402091-6d416620-55e8-448a-87dd-cecff28a1987.png)

# SWOT ANALYSIS
 ![image](https://user-images.githubusercontent.com/75977407/161402102-e720877e-e9d3-4cfd-a3e2-e869394f3547.png)

### STRENGTH
- 1. The game can help the player to predict the outcome of anothers move.
- 2. It helps to improve logic building and problem solving ability.
- 3. It helps develop coordination, fine motor skills and visual skills.
- 4. It can help to improve a person's concentration as well as strategic thinking
### WEAKNESS
GUI is not so attractive.
keyboard is only activated in the game.
### OPPORTUNITIES
Computer gaming
### THREATS
This game is addictive.
Only two players can play this game so users might attract to some other games.
### 4 W’s and 1 H
## WHO
Anyone can play this game.
It can be played by anyone who understand the rules of this game.
But two players are the limit for this game.
## WHAT
It is a game played by two players for fun and recreational purpose.
## WHEN
This game can be played whenever you are feeling bored or want to figure out ways, outcomes and situations of this game
It Can be used as timepass game like when you bored and you wants to put your time in Logical games you can go for this
## WHERE
It can be used in our laptops or desktops.
## HOW
This project is implemented by using loops, function call,branching statements,files other functionalities of C.
It Can be operated from Personal computer or laptop.

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

