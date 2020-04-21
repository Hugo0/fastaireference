---
description: Make the machine learn by trial and experimentation
---

# Reinforcement Learning

Reinforcement learning is used whenever there is an agent that acts in a dynamic environment. Some examples:

* Chess AI \(or any videogame AI\)
* Self-driving cars \(after processing video with [CV](computer-vision/)\)
* Robotics

Reinforcement learning works by letting the agent make decisions in a simulated environment, and _punish_ or _reward_ it according to its results. This is done repeatedly \(tens of thousands of times\). Eventually, the agent learns a reward function that maximizes rewards and minimizes punishments, thus becoming "intelligent".

This type of learning can be very effective, especially against traditional forms of artificial intelligence. In the world of chess, AlphaZero \(RL based\) [dominated ](https://www.chess.com/news/view/updated-alphazero-crushes-stockfish-in-new-1-000-game-match)Stockfish \(traditional AI\) shortly after its creation.

However, since this type of learning is mostly unsupervised, it sometimes can lead to surprising outcomes. For example, in [OpenAI's](https://openai.com/) Hide-and-Seek simulation, seekers ultimately learned to exploit the simulation physics engine and [effectively fly to find the hiders](https://www.youtube.com/watch?v=kopoLzvh5jY). 

![OpenAI Hide and Seek simulation](.gitbook/assets/image%20%288%29.png)

