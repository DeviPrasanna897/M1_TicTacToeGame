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
# TEST PLAN:


|Test ID |TestCase     | Description | Exp I/P | Exp O/P |
|--------|-------------|-------------|---------|---------|
|1    |Display of Game Board  |  Check if the graph for playing is being drawn or not.           |    No input.     |      3X3 graph is drawn.   |
|2    |Winner  |Check if Player1/Player2 got 3 of his inputs in vertical, horizontal or diagonal format.             |   'X' or 'O' i/p from the Player1/Player2.      |The Player1/Player2 won the game.|
|3    | Draw Game |Check for draw or tie in the game.            |   9 inputs from (Player1 and Player2).      |     The game ended with tie between the players.    |

# TestCase: Display Of Game Board
# checking game board i.e 3X3 matrix is displayed or not.
![image](https://user-images.githubusercontent.com/75977407/161399711-ac084c0d-ba79-48ce-ad7b-88b33cb29e07.png)
![image](https://user-images.githubusercontent.com/75977407/161399736-30ff802a-3713-4589-b39c-d0755b41d0f6.png)
![image](https://user-images.githubusercontent.com/75977407/161399744-65fd66a1-d0ef-496a-9ba8-7a6d49721638.png)
![image](https://user-images.githubusercontent.com/75977407/161399749-3c1a0d08-5087-4786-a03e-9fafc33080cb.png)
![image](https://user-images.githubusercontent.com/75977407/161399758-3511bb47-3bb7-4faf-923c-bfe7f4cba62a.png)
![image](https://user-images.githubusercontent.com/75977407/161399777-bf5d4d09-dc59-4c9a-99c7-46f434b74886.png)
![image](https://user-images.githubusercontent.com/75977407/161399778-e34654f7-15ec-4e28-af89-af89b39859a0.png)
![image](https://user-images.githubusercontent.com/75977407/161399806-ac9baeaa-e74b-4595-9ffa-626629aafa94.png)
![image](https://user-images.githubusercontent.com/75977407/161399809-24bf05f6-f91f-4b3c-8f97-d345d52fa8f9.png)
![image](https://user-images.githubusercontent.com/75977407/161399823-b071b8d5-0678-44ee-a740-595018ba344c.png)
# Hence Game Board(3X3) is displayed,TestCase passes. 

# TestCase: Checking for Draw or Tie in the Game.
![image](https://user-images.githubusercontent.com/75977407/161400999-cd6c6ef9-ca33-4545-a6b9-bf22f298529e.png)
![image](https://user-images.githubusercontent.com/75977407/161401005-9197c949-557e-44fc-b1f1-497c95f1cf45.png)
![image](https://user-images.githubusercontent.com/75977407/161401013-8804b035-518d-443e-b16e-3bd95f82843d.png)
## If user wants more clarifications and types ‘Y’ then this page will be displayed and after that they can continue the game
![image](https://user-images.githubusercontent.com/75977407/161401016-3bc69a5b-72ce-42e7-a986-40cc715c1b1a.png)
## Entering Player1 Name:Devi
 ![image](https://user-images.githubusercontent.com/75977407/161401024-27eedfc7-aa80-45f4-9af3-2ba7c78a7a53.png)
## Entering Player2 Name:Prasanna 
![image](https://user-images.githubusercontent.com/75977407/161401030-853adbf2-a117-4a0d-b132-d67a41289acc.png)
## Player1:Devi have to choose symbol ‘X’ or ‘O’
![image](https://user-images.githubusercontent.com/75977407/161401035-c8e59ea1-1bbc-49ee-ae6e-188877873bf7.png)
## After that entire screen will be cleared then players and leader board will be displayed.
## Then player1:Devi has choose to move after that Player2:Prasanna will get chance
![image](https://user-images.githubusercontent.com/75977407/161401052-74097925-accc-459b-9d97-fca9332e23a0.png)
![image](https://user-images.githubusercontent.com/75977407/161401056-d6bc4c2a-aa27-4a36-bb39-4a80d30c4171.png)
![image](https://user-images.githubusercontent.com/75977407/161401059-1e22e932-427d-42d1-bf4e-9c090f535109.png)
![image](https://user-images.githubusercontent.com/75977407/161401070-5731f1df-5277-404f-a99d-5cc76a1e44a6.png)
![image](https://user-images.githubusercontent.com/75977407/161401077-94b524b0-7390-41ed-be28-d9dd49225efa.png)
![image](https://user-images.githubusercontent.com/75977407/161401081-d030b175-2b52-49e7-84b1-eacab815bf39.png)
![image](https://user-images.githubusercontent.com/75977407/161401085-79f2502a-f5d6-438c-8eed-b33891874582.png)
![image](https://user-images.githubusercontent.com/75977407/161401090-34e648b2-7ad5-4a92-8ff9-466916e1dc94.png)
![image](https://user-images.githubusercontent.com/75977407/161401098-7f4cb132-7c62-4851-9a50-c229fe70ce45.png)

# TestCase: To check one of the two player wining
# Player1 Wins the Game:
![image](https://user-images.githubusercontent.com/75977407/161399923-510bbe0e-7a54-497b-aab0-b869749c067d.png)
![image](https://user-images.githubusercontent.com/75977407/161399927-3d3e01f0-6f88-431b-9e9d-3601fee6d63d.png)
## If user wants more clarifications and types ‘Y’ then this page will be displayed and after that they can continue the game
![image](https://user-images.githubusercontent.com/75977407/161399936-7d6191f3-0f7a-40d9-937e-7bfb1f927019.png)
![image](https://user-images.githubusercontent.com/75977407/161399940-29d42d79-ed66-4252-b4c2-123c58edcdb0.png)
## Entering Player1 Name: Ram
![image](https://user-images.githubusercontent.com/75977407/161399950-08d8e0a9-c4a7-4a84-a740-7df2a164a531.png)
## Entering Player2 Name:Bheem
![image](https://user-images.githubusercontent.com/75977407/161399968-c16cfbe3-543e-4eba-82ce-88010589b0d3.png)
## Player1:Ram have to choose symbol ‘X’ or ‘O’
 ![image](https://user-images.githubusercontent.com/75977407/161399978-4e6331dd-ac2f-421d-adfb-1186a4710268.png)

## After that entire screen will be cleared then players and leader board will be displayed.
## Then player1:Ram has choose to move after that Player2:Bheem will get chance
![image](https://user-images.githubusercontent.com/75977407/161400377-4a14f75f-4f48-4f42-9d2c-a92995227bd3.png)
![image](https://user-images.githubusercontent.com/75977407/161399998-8c6a9b69-0428-45e9-9cab-e1a102812b6e.png)
![image](https://user-images.githubusercontent.com/75977407/161400004-81076d9c-d026-40be-bc93-36bd1021bb03.png)
![image](https://user-images.githubusercontent.com/75977407/161400038-6b0af96a-5f5c-422c-b569-2876c489110e.png)
![image](https://user-images.githubusercontent.com/75977407/161400050-0ca41878-153c-4029-91ff-ecb25bffce41.png)
![image](https://user-images.githubusercontent.com/75977407/161400080-282b0e2b-4852-469b-bf9d-4c7076c083a6.png)
![image](https://user-images.githubusercontent.com/75977407/161400086-5d64bfbf-d5bf-4d82-b271-c4ed4a58af9d.png)
![image](https://user-images.githubusercontent.com/75977407/161400093-04610760-9b48-421e-b36f-b9258a16553d.png) 
# Hence Player1 Ram wins the Game.

# Player2 Wins:
## Entering Player1 Name:Krishna
![image](https://user-images.githubusercontent.com/75977407/161400461-4df573da-e356-47ed-8d38-d65bc5e810ab.png)
## Entering Player2 Name:Radha
![image](https://user-images.githubusercontent.com/75977407/161400469-511bd729-86f7-42ca-9d91-c8915015e00d.png)
## Player1:Krishna have to choose symbol ‘X’ or ‘O’
![image](https://user-images.githubusercontent.com/75977407/161400478-93bfffc2-3b7c-4d1f-a6c7-ae47ae22b370.png)
## After that entire screen will be cleared then players and leader board will be displayed.
## Then player1:Krishna has choose to move after that Player2:Radha will get chance.
![image](https://user-images.githubusercontent.com/75977407/161400490-52d90d91-c4e5-488f-9196-9279fe48cef0.png)
![image](https://user-images.githubusercontent.com/75977407/161400495-de23eefb-6a2c-4af4-8a9d-0951d0c464eb.png)
![image](https://user-images.githubusercontent.com/75977407/161400500-6d68187b-1f06-4c4a-a3a4-1bac1c0f2e4e.png)
![image](https://user-images.githubusercontent.com/75977407/161400504-15693856-c96e-4308-97bc-4b1a2133fbcc.png)
![image](https://user-images.githubusercontent.com/75977407/161400506-51ad574f-ef8d-4255-8fa2-d8cd96956f43.png)
![image](https://user-images.githubusercontent.com/75977407/161400511-3db4f43d-5249-4fa4-b739-212c5f4627bb.png)
![image](https://user-images.githubusercontent.com/75977407/161400520-1c2febf2-73f3-4872-978f-639d20f961c5.png)
![image](https://user-images.githubusercontent.com/75977407/161400659-34821978-3f21-45b9-9a4d-010437e29b43.png)
![image](https://user-images.githubusercontent.com/75977407/161400562-e78203f2-25a1-458e-8437-4b16d1b3c95c.png)
## Hence Player2 Radha wins the Game

# LEADERBOARD:
### The LeaderBoard values are stored in score.txt file 
### When the user like to see they have to press ‘2’ like the following
![image](https://user-images.githubusercontent.com/75977407/161400747-55cfaed9-8700-4032-86e6-0c8e4550c32a.png)
![image](https://user-images.githubusercontent.com/75977407/161400753-2d5a0411-f6e8-4a6a-9ddf-46e383f781cc.png)

# The scores of the players are stored in the separate file called "score.txt"
## This is done automatically user nedd not to do anything manually.
![image](https://user-images.githubusercontent.com/75977407/161401393-f11339d6-6ef3-45ee-a2e2-03ad98b9f8c4.png)
 

 

 
 


 



 

	
 
 

 
 


