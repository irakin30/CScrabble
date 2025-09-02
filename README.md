## How to Play
1. Running make with no arguments will immediately run a single instance of the client
2. You can choose to either host, join, or load a game. Hosts will automatically join their own game, those who choose join will need to supply an id. The port is 25595
3. Arrow keys are used to move the cursor and the keyboard is used to place letters down, upon pressing enter the board will be scored and it will be the opposing player's turn
4. If a word is invalid, your turn is not over, and you must retry until you place down a valid word
5. Backspace can be used to reset your board proposal

## Bugs
1. Scoring is also a little bit broken for edge cases and does not feature special tiles
2. No bag system(yet)

# Members

Zawad Dewan  
Lee Eisenberg  
Istab Rakin  

A simple recreation of the game scrabble on the command line interface (maybe with a seperate graphics window if we have the time) to be played with multiple players online.

Arrow keys are used to select a slot on the board to place a letter (carriage return). Then, a letter is chosen using the arrow keys (also carriage return).

Word Detection / Point Calculation - Zawad  
UI / Letter Placing - Istab  
Save / Load - Lee  
Multiplayer / Server - Probably all 3 of us  

2D arrays to store the board  
Hashmap / Dictionary to store dictionary  
Pipes to connect with others  
Queue for player turns and letters in the bag  
