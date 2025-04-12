# PPO CartPole Balancing

This project demonstrates the use of the Proximal Policy Optimization (PPO) reinforcement learning algorithm to solve the classic **CartPole-v1** environment from OpenAI Gym. The objective is to train an agent to balance a pole on a moving cart using reinforcement learning techniques.

## Project Overview

- **Algorithm**: Proximal Policy Optimization (PPO)
- **Environment**: CartPole-v1 (OpenAI Gym)
- **Framework**: Stable-Baselines3 (Python)
- **Objective**: Maximize the time the pole remains upright by learning an effective policy.

## Training Progress

The following visualizations show the agent’s performance at various training stages:

- **After 100 steps**  
  ![100 Steps](./PPO_cartpole_100_steps.gif)

- **After 1,000 steps**  
  ![1000 Steps](./PPO_cartpole_1000_steps.gif)

- **After 10,000 steps**  
  ![10000 Steps](./PPO_cartpole_10000_steps.gif)

- **After 100,000 steps**  
  ![100000 Steps](./PPO_cartpole_100000_steps.gif)

These animations illustrate how the agent's balancing behavior improves as training progresses.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PPO-CartPole.git
   cd PPO-CartPole
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the training notebook:
   ```bash
   jupyter notebook Cartpole.ipynb
   ```

## Requirements

- Python 3.8+
- `stable-baselines3`
- `gym`
- `matplotlib`
- `torch`
- `imageio`

To install all dependencies:
```bash
pip install stable-baselines3[extra] imageio matplotlib
```

## Files

- `Cartpole.ipynb` – Training script using PPO in Jupyter Notebook format
- `PPO_cartpole_*.gif` – Visual outputs showing agent performance at training milestones

## License

This project is released under the MIT License.

---

