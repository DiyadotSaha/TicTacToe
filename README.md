PLANNING: 
Text based or Graphical 
Graphical 
Pros: 
UI friendly
Visual 
Cons: 
More code
Maybe next step 
Have to figure out how to import pictures
Test based
Pros: 
Less code 
2D array 
Using |, X, O 
Cons: 
Not UI friendly 
Easier 
Cases
Computer vs player (easy)
Computer vs player 
Multiplayer
Presentation
Testbased: 
|     |     |     |
|     |     |     |
|     |     |     |                    

| X | O | X |
|     | O |     |
|     |     | O |
Graphical 






High Level Code Planning (Test Based) LEVEL: MULTIPLAYER: 
Methods: 
Description: 
A 2d array with  
menu(): 
Give user options 
Level 1: multiplayer
Pick character 
Level 2: against computer 
Pick character 
Level 3: against computer competitive
Pick character 
Exit 

clear_board(): 
print a new board on command “clear”
print_board(): 
prints after every turn 
score_tracker(user, row, col):
keeps track of score when played multiple times 
rules(user, row, col): 
Can’t pick already filled tile 
Three of the same character horizontal, vertically, diagonal 




