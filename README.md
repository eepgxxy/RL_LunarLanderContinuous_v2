# RL_LunarLanderContinuous_v2
Using reinforcement learning algorithm PPO from PARL to solve LunarLanderContinuous-v2 based on gym box2d environment.

LunarLanderContinuous-v2 is one of the environments from [gym box2d](https://gym.openai.com/envs/#box2d).
The goal is to train a LunarLander from knowing nothing about the environment to land safely on the correct position on the moon.


This repository includes the user-friendly jupyter notebook version of the solution.
The code is written using [PaddlePaddle](https://github.com/PaddlePaddle). The PPO algorithm from [PARL](https://github.com/PaddlePaddle/PARL) is being used. 

After training for about 3000 episodes, the current best evaluation reward is about 313 points per episode.
The current result is far better than the claimed pass points 200+. 

![train rewards](https://github.com/eepgxxy/RL_LunarLanderContinuous_v2/blob/master/train.png)

![eval rewards](https://github.com/eepgxxy/RL_LunarLanderContinuous_v2/blob/master/eval.png)

![result](https://github.com/eepgxxy/RL_LunarLanderContinuous_v2/blob/master/result.gif)
