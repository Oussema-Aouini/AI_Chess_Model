# AI Chess Bot - README

## Overview
This project contains an AI Chess Bot built using neural networks to play chess against human players or other engines (for example Stockfish). The bot can evaluate board positions and make decisions based on a trained model. Additionally, it can be rated by playing against Stockfish at various Elo levels.

## Features
- **AI-powered Chess Engine**: Uses a neural network to make moves.
- **Stockfish Integration**: Can play against Stockfish to evaluate its skill.
- **Customizable Elo Ratings**: Play against Stockfish with different Elo ratings to improve or test the bot's skill.
- **Visualization**: Displays the chessboard for easier understanding of moves.

## Prerequisites
To run the project, you need the following:
- **Python 3.7+**
- Google Colab or Jupyter Notebook
- **Required Libraries**:
  ```bash
  pip install numpy
  pip install tensorflow
  pip install python-chess
  pip install matplotlib

- **If you want to run the AI against Stockfish:**

    Download Stockfish from the official website.
    Place it in a folder and update the path in the notebook code
    
- **Execute the AI Chess Bot**

    Open the notebook and follow these steps:

    - **Load Dependencies**: Run the initial code cells to install and import required libraries.

    - **Train or Load the Model**: 

    Model training uses TensorFlow and takes the FEN strings as inputs to evaluate board positions.

    - **Play Against the Bot:**

    You can play interactively against the AI Bot by modifying the play_game function in the notebook to take your inputs.
    Bot vs Stockfish:

    Use the rate_bot function to simulate games between your bot and Stockfish. This will help you get an Elo rating for your AI.

    - **Game Visualization**

    The board visualization uses matplotlib and python-chess to display the game progress. You can adjust the visual settings as needed in the notebook.

    - **Tuning and Customization**
    Modify the play_nn function to fine-tune the AI's move evaluations.
    Adjust the search depth and other parameters to experiment with the bot’s playing strength.

    - **Common Issues and Troubleshooting**
    FileNotFoundError: If Stockfish cannot be found, double-check the path where you placed the engine and update the notebook accordingly.
    EngineError (UCI_Elo): Make sure you set the Stockfish Elo rating to at least 1320.
    Slow Performance: Neural network computations can be slow on local machines without or with a bad GPU.
