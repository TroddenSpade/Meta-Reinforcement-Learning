# Meta Reinforcement Learning Notebooks

**This Repository contains codes related to [FL-RL Project](). The complete codes and notebooks will be published soon.**


The purpose of this project is to implement and test the PyTorch codes of __Meta reinforcement Learning__ approaches from scratch.

## Requirements

* PyTorch
* Gym
* [Learn2Learn](http://learn2learn.net)
* [Cherry-RL](http://cherry-rl.net)
* [Mojuco-Py](https://github.com/openai/mujoco-py)

## Content
  - [x] Trust Region Policy Optimization
  - [x] MAML A2C
  - [x] MAML TRPO
  - [x] MAML PPO
  - [x] ANIL
  - [ ] SNAIL
  - [ ] Reptile
  
## Experiments
### Half Cheetah Environment
Training for 300 iterations.

<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/CheetahEnv/cheetah.png?raw=true" alt="plot1" width="500"/>

- TRPO-MAML trained model output
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/CheetahEnv/0.gif?raw=true" width="300"/>

- After 3 TRPO Update steps on forward task
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/CheetahEnv/1.gif?raw=true" width="300"/>

- After 3 TRPO Update steps on backward task
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/CheetahEnv/-1.gif?raw=true" width="300"/>


### Ant Environment
Training for 900 iterations.

<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/AntEnv/Ant.png?raw=true" alt="plot2" width="500"/>

- TRPO-MAML trained model output
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/AntEnv/0.gif?raw=true" width="300"/>

- After 5 TRPO Update steps on forward task
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/AntEnv/1.gif?raw=true" width="300"/>

- After 5 TRPO Update steps on backward task
<img src="https://github.com/TroddenSpade/Meta-Reinforcement-Learning/blob/main/results/AntEnv/-1.gif?raw=true" width="300"/>

## References

1. Finn, C., Abbeel, P. & Levine, S. Model-agnostic meta-learning for fast adaptation of deep networks. 34th Int. Conf. Mach. Learn. ICML 2017 3, 1856–1868 (2017).
2. Raghu, A., Raghu, M., Bengio, S. & Vinyals, O. Rapid Learning or Feature Reuse? Towards Understanding the Effectiveness of MAML. 1–21 (2019).
3. Mishra, N., Rohaninejad, M., Chen, X. & Abbeel, P. A Simple Neural Attentive Meta-Learner. 6th Int. Conf. Learn. Represent. ICLR 2018 - Conf. Track Proc. 1–17 (2017).
4. Schulman, J., Levine, S., Moritz, P., Jordan, M. I. & Abbeel, P. Trust Region Policy Optimization. 32nd Int. Conf. Mach. Learn. ICML 2015 3, 1889–1897 (2015).
5. Schulman, J., Wolski, F., Dhariwal, P., Radford, A. & Klimov, O. Proximal Policy Optimization Algorithms. 1–12 (2017).
