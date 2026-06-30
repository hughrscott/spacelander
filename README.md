---
library_name: stable-baselines3
tags:
- LunarLander-v3
- deep-reinforcement-learning
- reinforcement-learning
- stable-baselines3
model-index:
- name: PPO
  results:
  - task:
      type: reinforcement-learning
      name: reinforcement-learning
    dataset:
      name: LunarLander-v3
      type: LunarLander-v3
    metrics:
    - type: mean_reward
      value: 279.32 +/- 17.59
      name: mean_reward
      verified: false
---

# **PPO** Agent playing **LunarLander-v3**
This is a trained model of a **PPO** agent playing **LunarLander-v3**
using the [stable-baselines3 library](https://github.com/DLR-RM/stable-baselines3).

## Usage (with Stable-baselines3)
TODO: Add your code


```python
from stable_baselines3 import ...
from huggingface_sb3 import load_from_hub

...
```
