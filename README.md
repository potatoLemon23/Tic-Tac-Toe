# TIC TAC TOE
### pseudocode
1. Choose X's and O's: flip a coin
    1. Choose heads or tails
    2. Flip the coin
    3. If coin toss shows the chosen side, winner is X
    4. If coin toss shows the opposite side, loser is O
2. Game loop
    1. Player X chooses a square
    2. Chock if there are 3 in a row or the board is full
        1. Exit the game if true
    3. Player O chooses a square
    4. Check if there are 3 in a row or the board is full
        1. Exit the game if true
3. Check for winner or draw
    1. If 3 X's in a row: player X wins
    2. If 3 O's in a row: player O wins
    3. If the board is full and there's no winner: draw
    4. 
