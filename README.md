# Easy 21 Game Implementation using Reinforcement Learning

This assignment was completed for David Silver's Reinforcement Learning course.

Project files and plots available under the desktop folder.

# Game Definition

prog1.py defines the rules of the game, which is a slight variant of blackjack.

# Monte Carlo Method

prog2.py implements the Monte Carlo methods for calculating the value of the state. The state is defined by two parameters,

the sum of the cards the dealer holds and the sum of the cards the player holds. The value of a state is a float contained in

(-1.0, 1.0).

To run this file:

python prog2.py.

The output is given in the file Monte_Carlo_Control.png.

# SARSA Method

prog3.py implements the SARSA method, also for calculating the value of the state. Output is given in Sarsa_control.png.
