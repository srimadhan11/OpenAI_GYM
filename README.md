# OpenAI GYM
## CartPole-v1-simple
Agent is trained using simple RL algorithm, that works as following for each generation.
- Generate a batch of episodes
- Pick top n-percentile (n is hyperparameter) episodes based on reward
- Train the model on this n-percentile's state action pair


## CartPole-v1-DQN
Agent is trained using Q-learning algorithm.


---

**NOTE**: Each of the algorithm's implementation contains the following,
- A directory with rendered environment videos
- PyTorch model's parameter weights
- Jupyter Notebook for algorithm implementation

