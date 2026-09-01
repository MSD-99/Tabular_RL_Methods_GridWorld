# Tabular RL Methods Comparison: Monte Carlo, TD(0), SARSA & Q-Learning

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![RL](https://img.shields.io/badge/Reinforcement%20Learning-Tabular%20Methods-0052CC?style=for-the-badge)

This repository provides a comprehensive comparative analysis of four foundational tabular Reinforcement Learning algorithms on a Grid World environment. It evaluates both prediction (state-value estimation) and control (optimal policy finding) methods.

## 📌 Project Overview

**Notebook**: [`tabular_rl_gridworld_comparison.ipynb`](tabular_rl_gridworld_comparison.ipynb)

The implemented algorithms include:
1. **Monte Carlo Prediction**: First-visit MC to estimate the state-value function $V(s)$.
2. **TD(0) Prediction**: Temporal-Difference learning for continuous state-value updates.
3. **SARSA (On-Policy Control)**: TD-based method optimizing the policy that is actively being explored.
4. **Q-Learning (Off-Policy Control)**: TD-based method optimizing the greedy target policy regardless of exploration.

---

## 📊 Visualizations & Results

The notebook generates various heatmaps and learning curves comparing the algorithms' value function estimations, policy convergence, and learning efficiency.

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

*(Note: The exact visualizations correspond to value function heatmaps for MC vs TD, and optimal policies for SARSA vs Q-Learning).*

---

## 🚀 Quickstart

```bash
git clone https://github.com/MSD-99/Tabular_RL_Methods_GridWorld.git
cd Tabular_RL_Methods_GridWorld
pip install -r requirements.txt
jupyter lab
```
