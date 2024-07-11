# chess-engine

[TRY IT ONLINE](https://setday.github.io/chess-engine-online/)

A big thanks to [Alexander Serkov](https://github.com/setday) for the web implementation.

models/TORCH_100EPOCHS has shown a performance of approx. 1500 ELO during opening and middlegame.

It failes after about 20 moves. Simple algorithm to detect blunders is needed.

## Setup:

- Install Python dependencies:

    ```pip install -r requirements.txt```

- Put your data (.pgn files) into ```data/pgn/```. 

> The [dataset](https://database.nikonoel.fr/) that I used.

- Refer to ```engines/chess_engine.ipynb``` for further instructions and actions (TensorFlow)

- Or see ```engines/torch/predict```