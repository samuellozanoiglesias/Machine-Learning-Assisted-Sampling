# Machine Learning-Assisted Sampling — CECAM Workshop Tutorial

Welcome to the official repository for the hands-on tutorials of the **[CECAM Workshop: Machine learning-assisted sampling (Workshop 1513)](https://www.cecam.org/workshop-details/machine-learning-assisted-sampling-1513)**.

This course and its practical sessions were given by **Miguel Ruiz García** and **Samuel Lozano**.

---

## 📖 Context & Overview

This tutorial framework complements the lecture by **Miguel Ruiz García** on *"Learning Dynamical Laws from Trajectories Using GNNs"*. While Miguel's work focuses on frameworks like ActiveNet and Graph Neural Networks (GNNs) to infer deterministic and stochastic forces from observed physical trajectories, these hands-on sessions approach the broader challenge of learning rules and optimizing trajectories from a **Reinforcement Learning (RL)** and **Multi-Agent Reinforcement Learning (MARL)** perspective. 

By shifting the lens to RL, these tutorials explore how agents can autonomously discover optimal behaviors, interact in dynamically complex environments, and sample state-spaces efficiently, serving as a foundational pillar for machine learning-assisted sampling.

---

## 📚 Course Materials & Structure

This repository is organized to help you follow along with the workshop sessions:

* **Presentation:** The theoretical slides and framework presentation can be found in the main directory.
* **Notebooks (`.ipynb`) & Scripts (`.py`):** Ready-to-use Jupyter Notebooks for interactive learning, alongside raw Python files for local execution.
* **Pre-trained Agents (`./runs`):** Contains training logs and pre-trained policy weights. You can load these checkpoints to instantly visualize successful agent behaviors without waiting for the training process to complete.

---

## 🚀 Interactive Google Colab Notebooks

You can run the tutorials directly in your browser via Google Colab without installing any local dependencies:

### 👤 Single-Player Version (RL)
This version is designed for independent study, introducing the fundamentals of reinforcement learning and environment interaction.
* [**Open Single-Player Notebook in Colab**](https://colab.research.google.com/drive/1fJwbDrGGkGQUliZCd1W-jPIKLceULC8X?usp=sharing)

### 👥 Multi-Agent Extension (MARL)
This notebook introduces cooperation dynamics, which we will explore together during Tuesday's session.
* [**Open Multi-Agent Notebook in Colab**](https://colab.research.google.com/drive/1EG6q27kk7t2Y1BOed3QJ2X_G-YtZDA7Y?usp=sharing)

---

## 🛠️ Local Installation & Usage

If you prefer to run the code locally instead of using Google Colab, clone the repository and install the required dependencies:

```bash
git clone [https://github.com/samuellozanoiglesias/Machine-Learning-Assisted-Sampling.git](https://github.com/samuellozanoiglesias/Machine-Learning-Assisted-Sampling.git)
cd Machine-Learning-Assisted-Sampling
pip install -r requirements.txt
