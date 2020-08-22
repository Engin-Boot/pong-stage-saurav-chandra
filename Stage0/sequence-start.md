# Interaction Sequences

## Startup Sequence

1. player_profile will be used to login to the game and proceed, to know if the user is new or already on a level.

2. game_ui will be used to determine the theme of the game depenging on the user level and tasks he/she has completed.

3. game_fn will be used to actually play the game based on whatever theme the user is on.

## Movement Initiation

game_ui determines the speed, size and movement of the ball & racket.
game_fn determines the score if ball hits or miss the racket.

## One score

game_ui determines the speed, size and movement of the ball & racket.
game_fn determines if the ball hit the racket then increase the score and if it misses 3 times then reset to 0 and display "GAME OVER".
