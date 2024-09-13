# AI Chess Bot - README

## Overview
This project contains an AI Chess Bot built using neural networks to play chess against human players or other engines (e.g., Stockfish). The bot can evaluate board positions and make decisions based on a trained model. Additionally, it can be rated by playing against Stockfish at various Elo levels.

## Features
- **AI-powered Chess Engine**: Uses a neural network to make moves.
- **Stockfish Integration**: Can play against Stockfish to evaluate its skill.
- **Customizable Elo Ratings**: Play against Stockfish with different Elo ratings to improve or test the bot's skill.
- **Visualization**: Displays the chessboard for easier understanding of moves.

## Prerequisites
To run the project, you need the following:
- **Python 3.7+**
- **Google Colab** (optional for easy running) or Jupyter Notebook
- **Required Libraries**:
  ```bash
  pip install numpy
  pip install tensorflow
  pip install python-chess
  pip install matplotlib
