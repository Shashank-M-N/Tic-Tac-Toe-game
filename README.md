# Tic Tac Toe Game

## Overview
This project presents a Tic Tac Toe game implemented in Python using reinforcement learning techniques. Players have the option to engage in matches against a computer opponent choosing the required difficulty level or play it with another human like a 2 player game. Furthermore, users can train their own reinforcement learning policy to play Tic Tac Toe by executing the provided training notebook.

## Usage
1. Run `tic-tac-toe game.ipynb` to play interactive matches against a computer or another player.
2. Execute `tic-tac-toe training.ipynb` to train a custom reinforcement learning policy for playing Tic Tac Toe. 
> First, execute the `tic-tac-toe training.ipynb` notebook to train the policy. Next, run the `tic-tac-toe game.ipynb` notebook to play the game. Keep in mind that if you're using this for the first time, there won't be any pre-trained policy on your local system. After the initial training, you can directly run `tic-tac-toe game.ipynb` since the policy will be available in your local system. Enjoy playing! 😊

## Features
- Engage in matches against a computer player trained using reinforcement learning, with the option to choose the level of difficulty.
- Enjoy a classic 2-player game experience by playing with a friend.
- Train a custom reinforcement learning policy to play Tic Tac Toe.

## Results
- The computer's performance against a random move generator was exceptional. Notably, it has **never been defeated** and has secured **victory in over 98%** of matches.  
![Result of computer vs random moves](images/Computer%20vs%20Random%20moves.png)
- Here are the results of two computers playing against each other, with a **10% probability** of making random moves. It's evident that ties occur most frequently, approximately **73%** of the time. Moreover, observing from the perspective of the *first player (Player 1)*, we note that *Player 1* has a higher chance of winning compared to *Player 2*.  
![Result of computer vs computer](images/Computer%20vs%20Computer.png)

## Requirements
- Python 3
- Jupyter Notebook
- Libraries: numpy, pickle, Ipython, matplotlib

### A small note on the libraries used:
- **pickle:** Used for serializing and deserializing Python objects, allowing for saving and loading trained reinforcement learning policies.
- **numpy:** Essential for numerical computing, used for handling arrays and matrices efficiently.
- **IPython:** Provides enhanced interactive computing features, utilized for displaying clear and interactive outputs within Jupyter notebooks.
- **matplotlib:** A powerful plotting library used for visualizing data and results, enabling the creation of informative graphs and charts.*( Used only in `tic-tac-toe training.ipynb` notebook. )*

## Future Improvements
- Implement advanced reinforcement learning algorithms.
- Enhance user interface and interactivity for a more engaging experience.
- Optimize the training process to achieve faster convergence.