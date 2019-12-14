## Latent Belief Space Motion Planning under Cost, Dynamics, and Intent Uncertainty

Autonomous agents are limited in their ability to observe the world state. Partially observable Markov decision processes (POMDPs) model planning under world state uncertainty, but POMDPs with multimodal beliefs, continuous actions, and nonlinear dynamics suitable for robotics applications are challenging to solve. We present a dynamic programming algorithm for planning in the belief space over discrete latent states in POMDPs with continuous states, actions, observations, and nonlinear dynamics. Unlike prior belief space motion planning approaches which assume unimodal Gaussian uncertainty, our approach constructs a novel tree-structured representation of possible observations and multimodal belief space trajectories, and optimizes a contingency plan over this structure. We apply our method to problems with uncertainty over the reward or cost function (e.g., the configuration of goals or obstacles), uncertainty over the dynamics, and uncertainty about interactions, where other agents’ behavior is conditioned on latent intentions. Three experiments show that our algorithm outperforms strong baselines for planning under uncertainty, and results from an autonomous lane changing task demonstrate that our algorithm can synthesize robust interactive trajectories.


### Spotlight Video

{% include spotlight.html %}


### Paper and Citation

{% include paper_overview.html %}

```
@inproceedings{qiu2020poddp,
  title = {Latent Belief Space Motion Planning under Cost, Dynamics, and Intent Uncertainty},
  author = {Dicong Qiu and Yibiao Zhao and Chris L. Baker},
  booktitle = {Robotics: Science and Systems},
  month = {July},
  year = {2020},
  number = {16},
  pages = {69.1-69.10},
  address = {Corvalis, Oregon, USA}
}
```

### Experiment 1: Planning under cost function uncertainty

{% include exp1.html %}


### Experiment 2: Planning under dynamical mode uncertainty

{% include exp2.html %}


### Experiment 3: Latent intention-aware interactive lane changing

{% include exp3.html %}


### Comments

{% include disqus.html %}
