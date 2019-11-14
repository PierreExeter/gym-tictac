# Tic-Tac-Toe-Gym_Environment
This is an implementation of the tic-tac-toe game as a gym environment. 

The game is played on a grid that's 3 squares by 3 squares.
There are 2 players, one with X and the other with O. Players take turns putting their marks in empty squares.
The first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner.
A reward of +100 is given to the player wining the game.

## Installation and environment registration
```
git clone https://github.com/PierreExeter/gym-tictac.git
cd gym-tictac
pip install gym
pip install -e .
```

## Test your installation
```
python test_gym_tictac.py
```
