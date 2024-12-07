# Latency Optimization for Low-Latency Applications in 5G Networks

This repository contains a project aimed at optimizing latency for low-latency applications in 5G networks using Machine Learning, particularly reinforcement learning (RL). The project provides a simulated environment and a reinforcement learning implementation to dynamically adjust routing decisions, ensuring minimal latency for latency-sensitive applications.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
  - [Training the Model](#training-the-model)
  - [Testing the Model](#testing-the-model)
- [Project Structure](#project-structure)
- [Graphs](#graphs)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

5G networks enable a wide variety of applications, such as augmented reality, autonomous vehicles, and real-time gaming, that require ultra-low latency. Traditional latency optimization methods are static and cannot adapt to dynamic network conditions. This project uses reinforcement learning to optimize latency dynamically by adjusting routing paths and prioritizing resources based on real-time network conditions.

The RL agent learns to minimize latency by interacting with a simulated 5G network environment, where it chooses between routing paths and observes the effects on latency for latency-sensitive applications.

---

## Features
- Simulated 5G network environment for latency optimization.
- Q-learning-based reinforcement learning agent for dynamic decision-making.
- Real-time adjustment of routing paths to minimize latency.
- Performance evaluation through cumulative latency metrics and adaptive behavior.

---

## Technologies Used
- **Python**: Programming language for implementing the RL model and environment.
- **NumPy**: For numerical computations and data manipulation.
- **Gym**: For creating a custom RL environment to simulate network behavior.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Latency-Optimization-for-Low-Latency-Applications-in-5G-Networks.git
   cd Latency-Optimization-for-Low-Latency-Applications-in-5G-Networks
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

### Training the Model
Run the training script to train the Q-learning agent:
```bash
python main.py
```
This script trains the reinforcement learning agent in a simulated environment to optimize latency by learning optimal routing decisions.


## Project Structure
```
Latency-Optimization-for-Low-Latency-Applications-in-5G-Networks/
├── LICENCE                   # For Fair use
├── main.py                   # Project Code for reuse
├── project_notebook.ipynb    # To understand our project and see the results
├── requirements.txt          # Project dependencies
├── README.md                 # Project documentation
```

---

## Graphs
<p align="center">
  <img src="https://github.com/user-attachments/assets/168090ab-8099-41f4-8b24-22965a2d909c" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/6bbe4b7d-22a7-431a-8c96-86a0397d4946" alt="Reward Performance" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/89622734-3e22-43ee-90ff-c5049427fd97" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/958701f1-99bb-40a0-bcb9-4b290697e8aa" alt="Reward Performance" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/840177ff-c763-4a64-a4ea-71e108321c5a" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/c5eeec13-cde9-4670-8f88-3fda1533c07f" alt="Reward Performance" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/613dc5b0-d2a2-4a52-af14-239f8742f417" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/f3151afb-0bb5-4b11-901b-14da34268814" alt="Reward Performance" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/16b59580-b2f4-4d15-82ae-5479c8b85e4d" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/1c624aa7-6c97-47db-9343-964613a8162c" alt="Reward Performance" width="45%" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b95c7e87-a973-429f-b7bb-afd47960efc1" alt="Latency Performance" width="45%" />
  <img src="https://github.com/user-attachments/assets/dfaa192d-49b9-4656-b9d5-fcd487cce32c" alt="Reward Performance" width="45%" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/26140807-8bc9-47a4-99e1-15212455a47c" alt="Latency Performance" width="45%" />
</p>

<!--- ### Graph 1: Latency Performance Over Episodes
![Latency Performance](https://github.com/user-attachments/assets/8fe336bf-fc55-414e-8096-8b80231d1b72)

### Graph 2: Reward Performance Over Episodes
![Reward Performance](graphs/reward_performance.png)

### Graph 3: Latency Comparison Across Routes
![Route Comparison](graphs/route_comparison.png)
--->
---

## Future Improvements

1. **Advanced RL Algorithms**: Implement advanced techniques like Deep Q-Learning or Proximal Policy Optimization (PPO) for improved scalability.
2. **Real Data Integration**: Extend the environment to include real-world 5G traffic data and latency metrics.
3. **Multi-Agent Systems**: Develop multi-agent RL models to optimize latency across multiple network nodes simultaneously.
4. **Quality of Service (QoS)**: Incorporate QoS metrics into the reward system for more balanced optimization.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Happy optimizing!

