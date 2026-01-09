# 🟡 Deep Convolutional Q-Learning for Pac-Man

An end-to-end Reinforcement Learning project where an AI agent learns to play **Pac-Man** using **Deep Convolutional Q-Learning (DQN)**. The agent is trained directly from raw game frames, combining **Deep Learning** and **Q-Learning** to make optimal decisions in a dynamic environment.

---

## 🚀 Project Overview

This project implements a **Deep Q-Network (DQN)** agent that learns to play the classic Pac-Man game using trial-and-error interactions with the environment. The agent observes visual inputs (game frames), processes them using a **Convolutional Neural Network (CNN)**, and learns an optimal policy to maximize cumulative rewards.

The environment is built using **OpenAI Gymnasium (Atari)**, and the agent improves its performance over time through **experience replay** and **epsilon-greedy exploration**.

---

## 🧠 Key Concepts Used

- Reinforcement Learning
- Deep Q-Learning (DQN)
- Convolutional Neural Networks (CNNs)
- Markov Decision Process (MDP)
- Experience Replay
- Target Network Stabilization
- Epsilon-Greedy Policy

---

## 🕹️ Environment Details

- **Game**: Pac-Man (Atari)
- **Observation Space**: Raw pixel frames
- **Action Space**: Discrete movement actions
- **Framework**: OpenAI Gymnasium

---

## 🏗️ Model Architecture

- Input: Preprocessed game frames
- CNN layers for spatial feature extraction
- Fully connected layers for Q-value prediction
- Output: Q-values for each possible action

---

## ⚙️ Technologies & Tools

- Python
- PyTorch
- OpenAI Gymnasium (Atari)
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📈 Training Highlights

- Uses **Experience Replay Buffer** to reduce correlation between samples
- **Target Network** for stable Q-value updates
- Gradual reduction of exploration rate (epsilon decay)
- Mean Squared Error (MSE) loss for Q-learning updates

---

## 📊 Results

- The agent successfully learns to navigate the Pac-Man environment
- Shows improved survival time and score over training episodes
- Demonstrates effective policy learning from visual input alone

---

## 🧪 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   
2. Install Dependencies 
   ```bash
   pip install gymnasium[atari] torch numpy matplotlib

3. Run the notebook
   ```bash
   jupyter notebook Deep_Convolutional_Q_Learning_for_Pac_Man.ipynb


