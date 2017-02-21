# Atari - Deep Reinforcement Learning algorithms in TensorFlow

[![Build Status](https://travis-ci.org/brendanator/atari-rl.svg?branch=master)](https://travis-ci.org/brendanator/atari-rl)

Learning to play Atari in TensorFlow using Deep Reinforcement Learning

## Requirements

- Python 2/3
- [OpenAI Gym](https://gym.openai.com) with the [Arcade Learning Environment](https://github.com/mgbellemare/Arcade-Learning-Environment) - `pip install -r requirements.txt`
- [TensorFlow 1.0.0](https://www.tensorflow.org) - `pip install tensorflow`
- [SkipCTS](https:/github.com/mgbellemare/SkipCTS) - `git submodule update --init`

## Usage

- Show all options - `python main.py --help`
- Play a specific [Atari game](https://github.com/mgbellemare/Arcade-Learning-Environment/blob/master/src/games/Roms.cpp#L17) - `python main.py --game Breakout`

## Papers Implemented

- :white_check_mark: [Human Level Control through Deep Reinforcement Learning](http://www.nature.com/nature/journal/v518/n7540/pdf/nature14236.pdf)
    - `python main.py`
- :white_check_mark: [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/pdf/1509.06461.pdf)
    - `python main.py --double_q`
- :white_check_mark: [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/pdf/1511.06581.pdf)
    - `python main.py --dueling`
- :white_check_mark: [Learning to Play in a Day: Faster Deep Reinforcement Learning by Optimality Tightening](https://arxiv.org/pdf/1611.01606.pdf)
    - `python main.py --optimality_tightening`
- :white_check_mark: [Prioritized Experience Replay](https://arxiv.org/pdf/1511.05952.pdf)
    - `python main.py --replay_prioritized`
    - Only proportional prioritized replay is implemented
- :white_check_mark: [Unifying Count-Based Exploration and Intrinsic Motivation](https://arxiv.org/pdf/1606.01868.pdf)
    - `python main.py --exploration_bonus`
- :white_check_mark: [Deep Exploration via Bootstrapped DQN](https://arxiv.org/pdf/1602.04621.pdf)
    - `python main.py --bootstrapped`
- :white_check_mark: [Increasing the Action Gap: New Operators for Reinforcement Learning](https://arxiv.org/pdf/1512.04860.pdf)
    - `python main.py --persistent_advantage_learning`
- :white_check_mark: [Learning values across many orders of magnitudes](https://arxiv.org/pdf/1602.07714.pdf)
    - `python main.py --reward_scaling`
- :x: [Deep Recurrent Q-Learning for Partially Observable MDPs](https://arxiv.org/pdf/1507.06527.pdf)
- :x: [Safe and efficient Off-Policy Reinforcement Learning](https://arxiv.org/pdf/1606.02647.pdf)
- :x: [Continuous Deep Q-Learning with Model-based Acceleration](https://arxiv.org/pdf/1603.00748.pdf)
- :x: [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/pdf/1602.01783.pdf)

## Acknowledgements

- https://github.com/mgbellemare/SkipCTS - Used in implementation of [Unifying Count-Based Exploration and Intrinsic Motivation](https://arxiv.org/pdf/1606.01868.pdf)
- https://github.com/Kaixhin/Atari
- https://github.com/carpedm20/deep-rl-tensorflow
