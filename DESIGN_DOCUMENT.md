# Tic-Tac-Toe Game Design Document

## Main flow of the Game:
Start Screen:
    - The game loads and the user/player is prompted to press the enter key  to start the game
    - Enter player 1 name and player 2 name
    - Start
    - Player 1 is always X and player two is always O
    - Possible randomizer to roll for who goes first
Game Screen:
    - Game renders a tic-tac-toe box
    - Prompts the player to make a selection
        - the box is divided into 9 sections
        - horizontal axis is numbered
        - vertical axis is lettered
    - Player uses grid notation/predetermined placeholder to choose a spot to play
    - Game switches to the next player and repeats the process
End Screen:
    - Displays result along with prompt to reset the game


GAME FLOW

1. Render Tic-tac-toe box
2. Prompt player to make a selection
3. Player makes selection, then switches to the other player
4. Game concludes when one player has fulfilled a winning condtion
5. Prompt to Restart