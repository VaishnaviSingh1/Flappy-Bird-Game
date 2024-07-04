# Flappy-Bird-Game

This is a simple implementation of the Flappy Bird game using Python and Pygame. The game features a bird that the player controls to navigate through pipes without colliding with them. The goal is to achieve the highest score possible.

**Interface**

![WhatsApp Image 2024-07-04 at 8 25 01 PM](https://github.com/VaishnaviSingh1/Flappy-Bird-Game/assets/98222001/5246ec73-9225-439b-b801-c3bc3ee5e1f0)


## Prerequisites

Before running the game, you need to install the following libraries:

- `pygame`

You can install it using pip:

```bash
pip install pygame

**How to Run the Game**

1.Ensure you have Python installed on your machine. You can download it from python.org.

2.Clone this repository or download the source code files.

3.Navigate to the directory containing the source code files.

4.Install the required library (if not already installed) using the following command:
pip install pygame

5.Run the game using the following command:
python flappy_bird.py

**Game Controls**

Spacebar or Up Arrow Key: Make the bird flap its wings to fly upwards.
Escape Key: Quit the game.

**Game Features**

Welcome screen with instructions.
Player can start the game by pressing the Spacebar or Up Arrow Key.
User authentication system so that anyone can create an account and log in to the food order website.
Shopping cart functionality to add food items to the cart and order food.
Stripe payment gateway integration for online payments.
Order status update features.

**How the Game Works**

welcomeScreen()
Displays the welcome screen where the player can press Space or Up Arrow to start the game.

mainGame()
Contains the main game loop where the player controls the bird to navigate through the pipes. The score increases as the bird passes through the pipes.

isCollide(playerx, playery, upperPipes, lowerPipes)
Checks if the bird collides with any pipes or the ground.

getRandomPipe()
Generates positions for a pair of pipes (one upper and one lower) for the game.

**Acknowledgments**

This project was inspired by the popular Flappy Bird game.
Thanks to the Pygame community for their support and resources.




