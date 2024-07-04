# Flappy-Bird-Game

This is a simple implementation of the Flappy Bird game using Python and Pygame. The game features a bird that the player controls to navigate through pipes without colliding with them. The goal is to achieve the highest score possible.

**Interface**

![WhatsApp Image 2024-07-04 at 8 25 01 PM](https://github.com/VaishnaviSingh1/Flappy-Bird-Game/assets/98222001/5246ec73-9225-439b-b801-c3bc3ee5e1f0)


## Prerequisites

Before running the game, you need to install the following libraries

You can install it using pip:
```
pip install pygame
```

**How to Run the Game**
------

1.Ensure you have Python installed on your machine. You can download it from python.org.

2.Clone this repository or download the source code files.

3.Navigate to the directory containing the source code files.

4.Install the required library (if not already installed) using the following command:
```
pip install pygame
```

5.Run the game using the following command:
```
python flappy_bird.py
```

**Game Controls**
------

Spacebar or Up Arrow Key: Make the bird flap its wings to fly upwards.

Escape Key: Quit the game.


**How the Game Works**
---------------------------

1. welcomeScreen()

Displays the welcome screen where the player can press Space or Up Arrow to start the game.

2. mainGame()

Contains the main game loop where the player controls the bird to navigate through the pipes. The score increases as the bird passes through the pipes.

3. isCollide(playerx, playery, upperPipes, lowerPipes)

Checks if the bird collides with any pipes or the ground.

4. getRandomPipe()

Generates positions for a pair of pipes (one upper and one lower) for the game.

**Acknowledgments**
--------------------------------------

1. This project was inspired by the popular Flappy Bird game.

2. Thanks to the Pygame community for their support and resources.




