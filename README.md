# Tabular RL Methods Comparison: Monte Carlo, TD(0), SARSA & Q-Learning

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![RL](https://img.shields.io/badge/Reinforcement%20Learning-Tabular%20Methods-0052CC?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This repository compares four foundational tabular reinforcement-learning algorithms in a small Grid World. It covers prediction (state-value estimation) and control (policy learning).

## 📌 Project Overview

**Notebook**: [`tabular_rl_gridworld_comparison.ipynb`](tabular_rl_gridworld_comparison.ipynb)

The implemented algorithms include:
1. **Monte Carlo Prediction**: First-visit MC to estimate the state-value function $V(s)$.
2. **TD(0) Prediction**: Temporal-Difference learning for continuous state-value updates.
3. **SARSA (On-Policy Control)**: TD-based method optimizing the policy that is actively being explored.
4. **Q-Learning (Off-Policy Control)**: TD-based method optimizing the greedy target policy regardless of exploration.

---

## 📊 Visualizations & Results

The notebook generates value heatmaps, learned-policy views, and reward curves from its configured runs. These outputs illustrate algorithm behavior in this environment; they are not multi-seed convergence benchmarks.

### Sample Outputs
<p align="center">
  <img src="assets/tabular_rl_output_1.png" width="45%" alt="Output 1" />
  <img src="assets/tabular_rl_output_2.png" width="45%" alt="Output 2" />
</p>
<p align="center">
  <img src="assets/tabular_rl_output_3.png" width="45%" alt="Output 3" />
  <img src="assets/tabular_rl_output_4.png" width="45%" alt="Output 4" />
</p>
<p align="center">
  <img src="assets/tabular_rl_output_5.png" width="45%" alt="Output 5" />
  <img src="assets/tabular_rl_output_6.png" width="45%" alt="Output 6" />
</p>

The visualizations include value-function heatmaps for MC versus TD and learned policies for SARSA versus Q-Learning.

---

## 🚀 Quickstart

```bash
git clone https://github.com/MSD-99/Tabular_RL_Methods_GridWorld.git
cd Tabular_RL_Methods_GridWorld
pip install -r requirements.txt
jupyter lab
```

Open `tabular_rl_gridworld_comparison.ipynb` and run the cells in order. No external dataset or pretrained model is required.

## License

Released under the [MIT License](LICENSE).
