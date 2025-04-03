# aSwam: Adaptive Swimming Analysis Model

## Overview
aSwam is a research project focused on developing intelligent swarm behavior using deep reinforcement learning techniques. The project simulates swimming-like motion patterns in a multi-agent environment, where agents (drones) learn to coordinate their movements while avoiding obstacles and pursuing targets.

## Research Context
This project investigates the application of advanced deep reinforcement learning algorithms to solve complex multi-agent coordination problems. By combining LSTM networks with PPO (Proximal Policy Optimization), the system learns efficient swimming-like movement patterns that can be applied to various scenarios requiring coordinated motion control.

## Features
- Multi-agent reinforcement learning environment built with Pygame and Gymnasium
- LSTM-based neural network architecture for temporal sequence learning
- Proximal Policy Optimization (PPO) implementation for stable training
- Dynamic obstacle avoidance using potential fields
- Configurable simulation parameters for environment customization
- Real-time visualization of agent behaviors
- Stackable model architecture for enhanced learning capabilities

## Technical Stack
- Python 3.11+
- PyTorch for deep learning
- Stable-Baselines3 for reinforcement learning algorithms
- Pygame for simulation and visualization
- Gymnasium (OpenAI Gym) for environment interface
- NumPy for numerical computations

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/aSwam.git

# Navigate to the project directory
cd aSwam

# Create a virtual environment (recommended)
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install required dependencies
pip install -r requirements.txt
```

### Requirements
All dependencies are listed in `requirements.txt` with their minimum required versions:
- numpy >= 1.21.0
- pygame >= 2.6.0
- gymnasium >= 0.29.0
- torch >= 2.0.0
- stable-baselines3 >= 2.1.0
- matplotlib >= 3.7.0
- pandas >= 2.0.0
- scikit-learn >= 1.0.0

### System Requirements
- Python 3.11 or higher
- Sufficient RAM (recommended: 8GB+)
- GPU support (optional but recommended for faster training)

## Usage
The project includes two main Jupyter notebooks:
1. `swarmdrl_lstm.ipynb`: Implements LSTM-based learning for temporal sequence processing
2. `swarmdrl_stackking.ipynb`: Demonstrates advanced stacking techniques for enhanced model performance

To run the simulations:
1. Open either notebook in Jupyter Lab/Notebook
2. Execute the cells in sequence
3. Adjust hyperparameters as needed in the configuration sections

## Project Structure
- `swarmdrl_lstm.ipynb`: LSTM implementation for temporal learning
- `swarmdrl_stackking.ipynb`: Advanced stacking techniques
- `CONTRIBUTING.md`: Guidelines for contributing to the project
- `LICENSE`: Project license information

## Contributing
Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the terms specified in the LICENSE file.