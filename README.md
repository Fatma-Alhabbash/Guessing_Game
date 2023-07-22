# Guessing_Game

## Here is a fully functional project written in Python that shows how to create a simple Guessing Game

What is the game? 

Based on a program that generates a random number, the player should be able to determine this number after a few trials.


The functions used in this example are explained below:
1. ```show_levels()``` function:
    This function prints the levels and conditions of the game.
2. ```game_level_choice()``` function:
     This function enables the player to determine the level of the game.
3. ```set_game_settings(game_level)``` function:
    This function set the game setting on each level by taking the number of the level as a parameter.
4. ```start_play(limits, n_trials)``` function:
    This function takes ```limits``` of the number the program can generate and ```n_trials``` (number of trials) that are generated as output of ```set_game_settings(game_level)``` function as parameters to start the game.
5. ```play_again()``` function:
    This function determines if the user wants to play again or not.
6. ```play()``` function:
    This is the last function used to call other needed functions in the program and initialize the game.
