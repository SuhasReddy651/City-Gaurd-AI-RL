# 📝 City Guard AI - A Multi-Agent Reinforcement Learning System

This project, **City Guard AI**, is a multi-agent reinforcement learning game environment where two AI agents, **Heman** and **Shaktiman**, compete to eliminate the maximum number of enemies in a maze-like city. The environment includes dynamic elements like walls, health potions, and enemies. The agents are trained using reinforcement learning algorithms (DQN and A2C) to optimize their performance.

---

## 🚀 Key Features

1. **Game Environment**:
   - A fully observable environment based on the **Hunter Assassin Game** concept.
   - Includes walls, health potions, and dynamic enemies.
   - Supports competitive gameplay between two agents.

2. **Reinforcement Learning Algorithms**:
   - **Shaktiman**: Trained using Deep Q-Network (DQN).
   - **Heman**: Trained using Advantage Actor-Critic (A2C).

3. **Reward System**:
   - Positive and negative rewards based on steps, health, and kills.
   - Agents learn optimal strategies over multiple episodes.

4. **Evaluation**:
   - Testing includes random agents vs. trained agents and a competitive test between both agents.
   - Includes visualizations of training rewards and performance comparisons.

---

## 🛠️ Tech Stack

- **Programming Language**:  
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)

- **Frameworks & Libraries**:  
  [![PyGame](https://img.shields.io/badge/PyGame-00CCBB?style=for-the-badge&logo=python&logoColor=white)](#)  
  [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](#)  
  [![Matplotlib](https://img.shields.io/badge/Matplotlib-008080?style=for-the-badge&logo=python&logoColor=white)](#)  

---

## 🏗️ Project Structure

- `Assets/` → Directory containing all the game assets, including images and fonts:
- `Check Points/` → Directory for saved model weights:
  - `Grid_Q_net_1990.pkl` → Saved weights for the DQN agent (Shaktiman).
  - `actor_net_1990.pkl` → Saved weights for the A2C agent (Heman).
- `Plots/` → Directory for training and testing visualizations:
  - `Output_Both_Policy.png`, `Testing_Both_Policy.png` → Visualizations of both agents competing.
  - `Output_Heman-random.png`, `Testing_Heman-random.png` → Performance of Heman (trained vs random).
  - `Output_Hero-random.png`, `Testing_Hero-random.png` → Performance of Shaktiman (trained vs random).
- `training.py` → Python script for training the agents using DQN and A2C algorithms.
- `testing_bothweights.py` → Script for testing both agents with their respective trained weights.
- `testing_heman_random.py` → Script for testing Heman with random actions.
- `testing_hero_random.py` → Script for testing Shaktiman with random actions.
