# Reinforcement Learning: Deeq Q Learning Network (DQN) Agent playing Atari Breakout

* Implementation in Tensorflow of Deep Q Learning Network (DQN) in Atari's Breakout environment, .
  

https://github.com/EnricoBos/dqn_Atari_breakout/assets/44166692/1f8dd0d7-81d4-495d-8969-384cb2a0a5ab




## Environment
* Python 3.10.10 
* OpenAI Gymnasium
	- V.0.28.1
	- Atari environment used: `BreakoutNoFrameskip-v4`
* Tensorflow V.2.10.0

## Implementation
* Deep Q Learning Network with the following improvements:
	- Experience Replay
	- Fixed Target Q-Network
	- TD error loss function with: *Q<sub>target</sub> = reward + (1-terminal) * (gamma * Q<sub>max</sub>(s’)
)*


## Usage (Ensure you define a file save path)
* Traing the DQN Agent: `my_breakout_dqn.py`
* Testing the DQN Agent: `my_breakout_dqn_eval.py`


## Learning Curve
* ![learning_curve_atari_dqn_breakout](https://github.com/EnricoBos/dqn_Atari_breakout/assets/44166692/47ed29aa-b58e-45f8-b7ad-f83f553d015c)
