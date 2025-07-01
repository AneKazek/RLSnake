# Snake Game AI with PyTorch

This repository contains an implementation of a Snake game AI agent trained using Reinforcement Learning with PyTorch. The project demonstrates how to build an intelligent agent that learns to play the classic Snake game by maximizing its score.

## Features

- **Snake Game Environment**: A custom-built Snake game environment using Pygame.
- **Deep Q-Network (DQN)**: An AI agent trained with a Deep Q-Network to learn optimal policies.
- **PyTorch Implementation**: Leveraging PyTorch for building and training the neural network model.
- **Training and Evaluation**: Scripts for training the AI agent and evaluating its performance.
- **Visual Play**: Option to visualize the AI playing the game during training or evaluation.

## Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8+
- pip (Python package installer)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RLSnake.git
   cd RLSnake
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv rlsnake_env
   .\rlsnake_env\Scripts\activate # On Windows
   source rlsnake_env/bin/activate # On macOS/Linux
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the AI Agent

To train the AI agent, run the `agent.py` script:

```bash
python notebooks/reinforcement_learning_pytorch_pygame/agent.py
```

To play the game manually, run the `snake_game_human.py` script:

```bash
python notebooks/reinforcement_learning_pytorch_pygame/snake_game_human.py
```

## Project Structure

```
RLSnake/
├── .gitignore
├── LICENCE.txt
├── README.md
├── requirements.txt
└── notebooks/
    └── reinforcement_learning_pytorch_pygame/
        ├── agent.py          # Main script for training the AI agent
        ├── game.py           # Snake game environment logic
        ├── model.py          # Deep Q-Network model definition
        ├── helper.py         # Utility functions
        ├── snake_game_human.py # Script to play the game manually
        ├── arial.ttf         # Font file for Pygame
        └── LICENSE           # License for the original notebook
```

## License

This project is licensed under the MIT License - see the `LICENCE.txt` file for details.

## Acknowledgments

- This project is inspired by various Reinforcement Learning tutorials and implementations of the Snake game.