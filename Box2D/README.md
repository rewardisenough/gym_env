# Video of trained agents:



https://user-images.githubusercontent.com/68491459/201793697-11ed703e-b4a0-450e-a567-1b326d5665c8.mp4

* [X] Lunar Lander
* [ ] Car Racing. Wasn't able to solve due to a what seemed like a bug in Ray RLlib. Others have it as well:
  https://github.com/ray-project/ray/issues/15089, https://discuss.ray.io/t/saving-gym-environment-video-with-rllib/396.
* [ ] Bipedal Walker. Wasn't able to solve due to what also seemed like a bug that's preventing the agent from learning. Others have it as well: https://github.com/ray-project/ray/issues/7415. Although it's stated that several algorithms such as PPO was successful at solving this enviornment, none of the algorithm worked for me except for algorithm called "ARS" which seemed to learn well. However, it was not sample efficient and took a long time to start learning.

Goal is to come back to these enviornment and implement or tweak the algorithms to solve these unsolved enviornments. 

Potential reference: https://github.com/ray-project/ray/issues/15089.
