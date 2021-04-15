# TEST PLAN:

## Table no: High level test plan

|Test ID | Description | Exp I/P | Exp O/P |
|--------|-------------|---------|---------|
|H_01    |  Check if the graph for playing is being drawn or not.           |    No input     |      3X3 graph is drawn   |
|H_02    |Check if player/computer got 3 of his inputs in vertical, horizontal or diagonal format.             |   'X' or 'O' i/p from the user      |The user/computer won the game.|
|H_03    | Check for draw.            |   9 inputs from (user+computer)      |     The game is over    |



## Table no: Low level test plan

|Test ID | Description | Exp I/P | Exp O/P |
|--------|-------------|---------|---------|
|L_01    | Check if the basic requirement to the game  (3x3 playing field) is created or not.This 3X3 squares is the first step in the program to play the game |    Not expected                   any input from the user |  3X3 playing field  |
|L_02    |  Play proceeds with the opponents alternately placing their marks in any unoccupied cell. check if any player finishes  with 3 marks in a row, where a row can be either                  vertical, horizontal, or diagonal. |   'X' or 'o' i/p from the two players alternatively      |   The player 1/2 won the game.      |
|L_03    |   Check if all the 9 squares are full,the game is over and no player can get the 3 marks in a row the game is draw , if any one of the player get the 3 marks in a row                     that player will win the game           |  9 inputs from the users.       |                The game is over/Ended.       The player 1/2 won the game or The game is draw/tie |



