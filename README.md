# Robust-RL-Papers


[![Awesome](https://awesome.re/badge.svg)](https://github.com/ClementineY/Robust-RL-Papers) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/ClementineY/Robust-RL-Papers?color=green) 

📚Must-read Papers on Robust Reinforcement Learning

---

*"Here are some other paper lists you might be interested in:*

💡 **[Reinforcement-Learning-Papers](https://github.com/yingchengyang/Reinforcement-Learning-Papers):** Related papers for reinforcement learning, including classic papers and latest papers in top conferences.

🔬 **[Reinforcement-Learning-Papers](https://github.com/zjunlp/KnowledgeEditingPapers):**  List of Top-tier Conference Papers on Reinforcement Learning (RL)，including: NeurIPS, ICML, AAAI, IJCAI, AAMAS, ICLR, ICRA, etc. 

*We sincerely invite you to dive into these collections of papers and resources, each offering a distinct journey of exploration and discovery.*  :partying_face:”

## 🔔 News

## 📜Content

- [Robust RL Papers](#robust-rl-papers)
  - [Foundation](#foundation)
  - [Transition and Reward Robust Design](#transition-and-reward-robust-design)
  - [Disturbance Robust Design](#disturbance-robust-design)
  - [Action Robust Design](#action-robust-design)
  - [Observation Robust Design](#observation-robust-design)
  - [Generalization to New or Unseen Environments](generalization-to-new-or-unseen-environments)
  - [Addressing Uncertainty In Model Parameters](#addressing-uncertainty-in-model-parameters)
  - [Geometric Analysis](#geometric-analysis)
  - [Maximum Entropy](#maximum-entropy)



## Robust RL Papers

---


### Foundation

1. **Robust Reinforcement Learning**

   *Jun Morimoto, Kenji Doya.* [PDF](https://proceedings.neurips.cc/paper_files/paper/2000/file/e8dfff4676a47048d6f0c4ef899593dd-Paper.pdf), *Advances in Neural Information Processing Systems*, vol. 13, MIT Press, 2000

2. **Robust Markov Decision Processes**

   *Wolfram Wiesemann, Daniel Kuhn, Berç Rustem.* [DOI](https://doi.org/10.1287/moor.1120.0566), *Mathematics of Operations Research*, 38(1):153-183, 2012

3. **Robust Markov Decision Processes: Beyond Rectangularity**
   
   *Vineet Goyal, Julien Grand-Clément.* [DOI](https://doi.org/10.1287/moor.2022.1259), *Mathematics of Operations Research*, 48(1):203-226, 2022.

4. **Robust Reinforcement Learning: A Review of Foundations and Recent Advances**

   *Johannes Moos, Kai Hansel, Hesham Abdulsamad, Sebastian Stark, David Clever, Jan Peters.* [DOI](https://doi.org/10.3390/make4010013), *Machine Learning and Knowledge Extraction*, 4(1):276-315, 2022. 

---


### Transition and Reward Robust Design(Dealing with distributional shift in the environment dynamics)

1. **Policy Gradient for Rectangular Robust Markov Decision Processes**

   *Navdeep Kumar, Esther Derman, Matthieu Geist, Kfir Y. Levy, Shie Mannor.* [PDF](https://proceedings.neurips.cc/paper_files/paper/2023/file/ba8aee784ffe0813890288b334444eda-Paper-Conference.pdf), *Advances in Neural Information Processing Systems*, vol. 36, pp. 59477-59501, Curran Associates, Inc., 2023

2. **Twice Regularized Markov Decision Processes: The Equivalence between Robustness and Regularization**

   *Esther Derman, Yevgeniy Men, Matthieu Geist, Shie Mannor.* [PDF](https://arxiv.org/abs/2303.06654), arXiv:2303.06654 [cs.LG], 2023

3. **Beyond Discounted Returns: Robust Markov Decision Processes with Average and Blackwell Optimality**

   *Julien Grand-Clement, Marek Petrik, Nicolas Vieille.* [PDF](https://arxiv.org/pdf/2312.03618.pdf), arXiv:2312.03618 [math.OC], 2023

4. **A General Framework for Learning-Based Distributionally Robust MPC of Markov Jump Systems**

   *Michel Schuurmans, Panagiotis Patrinos.* [DOI](https://doi.org/10.1109/TAC.2023.3237999), *IEEE Transactions on Automatic Control*, vol. 68, issue 5, pp. 2950–2965, Institute of Electrical and Electronics Engineers, 2023

5. **Double Pessimism is Provably Efficient for Distributionally Robust Offline Reinforcement Learning: Generic Algorithm and Robust Partial Coverage**

   *Jose Blanchet, Miao Lu, Tong Zhang, Han Zhong.* [PDF](https://arxiv.org/abs/2305.09659), arXiv:2305.09659 [cs.LG], 2023

6. **Memory Gym: Towards Endless Tasks to Benchmark Memory Capabilities of Agents**

   *Marco Pleines, Matthias Pallasch, Frank Zimmer, Mike Preuss.* [PDF](https://arxiv.org/abs/2309.17207), arXiv:2309.17207 [cs.LG], 2024

---


### Disturbance Robust Design

1. **Characterising the Robustness of Reinforcement Learning for Continuous Control using Disturbance Injection**

   *Catherine Glossop, Jacopo Panerati, Amrit Krishnan, Zhaocong Yuan, Angela P. Schoellig.* [PDF](https://openreview.net/pdf?id=IgXOXUVObLB), 2022

---


### Action Robust Design

1. **Tactics of Robust Deep Reinforcement Learning with Randomized Smoothing**

   *Chung-En Sun, Sicun Gao, Tsui-Wei Weng.* [PDF](https://openreview.net/pdf?id=sRop0N5NYV), 2024

---


### Observation Robust Design

1. **Corruption-Robust Algorithms with Uncertainty Weighting for Nonlinear Contextual Bandits and Markov Decision Processes**

   *Chenlu Ye, Wei Xiong, Quanquan Gu, Tong Zhang.* [PDF](https://proceedings.mlr.press/v202/ye23d/ye23d.pdf), *Proceedings of the 40th International Conference on Machine Learning*, in *Proceedings of Machine Learning Research* 202:39834-39863, 2023.

---


### Generalization to New or Unseen Environments

1. **Learning Invariant Representations for Reinforcement Learning without Reconstruction**

   *Amy Zhang, Rowan McAllister, Roberto Calandra, Yarin Gal, Sergey Levine.* [PDF](https://arxiv.org/pdf/2006.10742.pdf) arXiv:2006.10742, 2020

---


### Addressing Uncertainty in Model Parameters

1. **Robust Reinforcement Learning using Offline Data**

   *Kishan Panaganti, Zaiyan Xu, Dileep Kalathil, Mohammad Ghavamzadeh.* [PDF](https://openreview.net/forum?id=AK6S9MZwM0), *Advances in Neural Information Processing Systems*, 2022.

---


### Geometric Analysis

1. **The Geometry of Robust Value Functions**

   *Kaixin Wang, Navdeep Kumar, Kuangqi Zhou, Bryan Hooi, Jiashi Feng, Shie Mannor.* [PDF](https://arxiv.org/pdf/2201.12929.pdf), arXiv:2201.12929  [cs.LG], 2022

---


### Maximum Entropy 

1. **Maximum Entropy RL (Provably) Solves Some Robust RL Problems**

   *Benjamin Eysenbach, Sergey Levine.* [PDF](https://arxiv.org/pdf/2103.06257.pdf), arXiv:2103.06257 [cs.LG], 2021


