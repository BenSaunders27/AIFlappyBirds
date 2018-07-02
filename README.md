# AIFlappyBirds
Code to play AI Flappy Birds on PyGame

This is built using Genetic Algorithms with a Neural Network processing, taking the inputs of "X-Distance to Wall", "Y-Distance to Wall" and "Velocity" to decide whether to jump in a certain moment, using weights learnt over time. Initially set-up with random weights, each generation learns from the last by taking the top-5 performing birds and adding a slight extra randomness to their weights, and thus improve the performance.  

Set up using Pygame, so this is a dependency to install. Install via Pip for Python.


