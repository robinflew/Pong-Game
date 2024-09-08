This is the project I used as my first attempt to learn Game Development. (I also used this as my Capstone Project for my High School graduation)
For GitHub upload:

# Pong Game in Python

## A classic two-player Pong game implemented using Python's Turtle graphics

### Table of Contents
1. [Introduction](#introduction)
2. [Game Setup](#game-setup)
3. [Game Objects](#game-objects)
4. [Game Controls](#game-controls)
5. [Game Logic](#game-logic)
6. [How to Run](#how-to-run)

### Introduction
This project is a Python implementation of the classic Pong game using the Turtle graphics library. It features a two-player setup where players can control paddles to hit a ball back and forth.

### Game Setup
The game window is set up using Turtle's Screen object. It's configured with a black background and dimensions of 800x600 pixels. The game uses Turtle's tracer function to control the screen updates for smoother animations.

### Game Objects
1. **Paddles**: Two paddles (paddle_a and paddle_b) are created using Turtle objects. They are positioned on opposite sides of the screen and can move up and down.
2. **Ball**: A ball object is created that moves across the screen. Its direction changes upon hitting the top/bottom borders or the paddles.
3. **Scoreboard**: A Turtle object (pen) is used to display and update the score at the top of the screen.

### Game Controls
- Player A (left paddle) uses 'W' and 'S' keys to move up and down.
- Player B (right paddle) uses 'Up' and 'Down' arrow keys to move up and down.

### Game Logic
The main game loop handles:
1. Ball movement
2. Border checking to keep the ball within the game area
3. Scoring when the ball passes a paddle
4. Collision detection between the ball and paddles
5. Updating the score display

### How to Run
To run the game, ensure you have Python and the Turtle graphics library installed. Then, simply run the Python script. The game will start immediately, and players can use their respective keys to control the paddles.

Note: This game runs in an infinite loop. To exit, you'll need to close the game window manually.
