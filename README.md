# Teach AI to play Snake Using Reinforcement Learning

# AI Snake Game with Reinforcement Learning

This project aims to train an AI agent to play the game of Snake using reinforcement learning techniques. The implementation utilizes PyTorch for deep learning and Pygame for creating the game environment.

## Prerequisites

Before getting started, make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- Pygame

You can install PyTorch and Pygame using pip:

```bash
pip install torch pygame
```

## Project Structure

The project is organized into the following files and directories:

- `agent.py`: Contains the implementation of the AI agent using a reinforcement learning algorithm.
- `game.py`: Implements the Snake game environment using Pygame.
- `helper.py`: The main script to train the AI agent.
- `README.md`: Provides information about the project.

## Training the AI Agent

To train the AI agent to play Snake, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the following command:

```bash
python train.py
```

4. The training process will start, and you can monitor the progress in the terminal.
5. Once training is complete, the trained model weights will be saved as `model.pth`.

## Watching the AI Agent Play

To watch the trained AI agent play the Snake game, execute the following steps:

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Run the following command:

```bash
python agent.py
```

4. The game window will open, and you can observe the AI agent playing the Snake game.

## Customizing the Training

You can modify various aspects of the training process by adjusting the parameters defined in the `train.py` file. Some of the parameters you may want to tweak include:

- `num_episodes`: The number of training episodes.
- `max_steps`: The maximum number of steps per episode.
- `epsilon_start`: The initial exploration rate.
- `epsilon_end`: The final exploration rate.
- `epsilon_decay`: The rate at which exploration decreases.
- `learning_rate`: The learning rate for the neural network.
- `gamma`: The discount factor for future rewards.

Feel free to experiment with these parameters to achieve optimal training results.

## Conclusion

By following this guide, you should be able to train an AI agent to play the Snake game using reinforcement learning. Enjoy exploring the possibilities of AI and gaming with this project!

If you have any questions or encounter any issues, please don't hesitate to reach out.

Happy coding!



