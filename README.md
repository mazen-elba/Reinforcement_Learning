### Reinforcement Learning (RL) Terminologies
- **Agent** - learner and decision maker.
- **Environment** - location where the agent learns and decides what actions to perform.
- **Action** - a set of actions which the agent can perform.
- **State** - status of the agent in the environment.
- **Model** - the agent's view of the environment, which maps state-action pairs to probability distributions over states.
    - Not every RL agent uses a model of its environment
- **Reward** - for each action selected by the agent, the environment provides a reward (ie; scalar value).
- **Policy** - decision-making function (control strategy) of the agent, which represents a mapping from situations to actions.
- **Value Function** - mapping from states to real numbers, where the value of a state represents the long-term reward (achieved starting from that state), and executing a particular policy.
- **Function Approximator** - the problem of inducing a function from training examples.
    - Standard approximators: decision trees, neural networks, and nearest-neighbor methods
- **Markov Decision Process (MDP)** - probabilistic model of a sequential decision problem, where states can be perceived exactly, and the current state and action selected determine a probability distribution on future states.
    - Outcome of applying an action to a state depends only on the current action and state (not on preceding actions or states).
- **Dynamic Programming (DP)** - a class of solution methods for solving sequential decision problems with a compositional cost structure.
- **Monte Carlo** - a class of solution methods for learning of value functions, which estimates the value of a state by running many trials starts at that state, then averages the total rewards received on those trials.
- **Temporal Difference (TD)** - a class of learning methods, based on the idea of comparing temporally successive predictions.

# RL Algorithms
## I) Model-Free RL
### I.1) Policy Optimization/Policy-Iteration methods
- Policy Gradient (PG)
- Asynchronous Advantage Actor-Critic (A2C/A3C)
- Proximal Policy Optimization (PPO)
- Trust Region Policy Optimization (TRPO)
### I.2) Q-Learning/Value-Iteration methods
- Deep Q Neural Network (DQN)
- C51
- Distributional RL with Quantile Regression (QR-DQN)
- Hindsight Experience Replay (HER)
### I.3) Hybrid (Policy Optimization + Q-Learning)
- Deep Deterministic Policy Gradients (DDPG)
- Twin Delayed Deep Deterministic Policy Gradients (TD3)
- Soft Actor-Critic (SAC)
## II) Model-Based RL
### II.1) Learn the Model
- World Models
- Imagination-Augmented Agents (I2A)
- Model-Based Priors for Model-Free RL (MBMF)
- Model-Based Value Expansion (MBVE)
### II.2) Given the Model
- AlphaZero
    
# References
- Robert Moni's "Reinforcement Learning algorithms -- an intuitive overview"
