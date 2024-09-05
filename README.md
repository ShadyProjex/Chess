# Chess AI Engine

## Overview

This project is a Chess AI Engine written in C++. The engine allows a player to play chess against an AI that calculates and suggests the best possible moves using a scoring algorithm. The engine is built with various advanced features, including a custom priority queue to rank moves, depth-based move evaluation, and consideration of special chess rules like en passant and castling.

## Features

- **Chess Board Representation**: The chessboard is represented as an 8x8 grid, where each position can hold a unique pointer to a `GamePiece` object.
- **Move Evaluation**: 
  - The engine evaluates moves by calculating scores based on several factors such as the potential to check the opponent, capture pieces, or avoid being threatened by weaker pieces.
  - The evaluation considers multiple depths, assessing the consequences of a move and the opponent's possible responses.
- **Priority Queue**: A custom priority queue template is implemented to keep track of the top 5 moves based on their scores.
- **Special Moves**: 
  - The engine supports special moves such as en passant and castling.


### Prerequisites

- A C++17 compatible compiler (e.g., GCC, Clang, MSVC)
- CMake (optional, for building the project)
- Basic knowledge of C++ and chess rules
