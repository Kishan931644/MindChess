
# MindChess

This is a simple chess engine/interface created using flask.
It uses chessboard.js and chess.js for the logic of the frontend chessboard, and python chess for the
logic of the backend chessboard. All calculation is done on the backend using python.



Algorithm
    
    1. Initialize Chess Board
        Set up the board using a FEN string.
    
    2. Define Piece Values and Evaluation Tables
        Assign values to pieces and set up position evaluation tables.

    3. Evaluate Board Position
        Calculate the score based on piece values and positions.
    
    4. Minimax Search Algorithm
        If at depth 0, return the board score.
        For each legal move:
            Apply move and recurse with reduced depth.
            Undo move and choose best score.

    5. Alpha-Beta Pruning
        Use alpha and beta to prune non-promising branches.

    6. Find the Best Move
        Determine the best move using minimax with alpha-beta pruning.

    7. Output the Best Move
        Print or return the best move.
## Deployment


In order to run this application on your own machine, please install flask and python chess.

Install flask by running:

```bash
  pip install flask
```
Install python chess by running:
```bash
  pip install python-chess[uci,gaviota]
```
## Demo

https://drive.google.com/file/d/1CwX3Ua9Gv_1TA7XDEHb8rWcjRTAI-m7g/view?usp=sharing

