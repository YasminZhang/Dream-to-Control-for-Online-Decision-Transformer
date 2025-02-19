# Dream-to-Control-for-Online-Decision-Transformer

[![Static Badge](https://img.shields.io/badge/DODT-arxiv_link-blue)
](https://arxiv.org/abs/2410.11359)

This is the implementation of  Dreamer for the Online Decision Transformer. It uses the Online Decision Transformer as the baseline model, then in parallel, it trains a Dreamer model. After both models are trained, the trajectories from Dreamer are used to train the Online Decision Transformer Model for better learning processes.

It has two versions

1. "main.py" uses datasets from D4RL (This is the DODT) 
2. "new_main_online.py" has no dataset uses, and ONLY use data trajectories from Dreamer model.


## How to use

Install dependencies:
```bash
pip install -r pip.txt
```

## Start

To run Dream to Control for Online Decision Transformer with dataset:
```bash
python main.py
```

To run Dream to Control for Online Decision Transformer without dataset:
```bash
python new_main_online.py
```

## For any questions, please contact:
e*********@g.**la.edu
