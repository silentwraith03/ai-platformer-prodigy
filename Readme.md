## Project Overview
AI Platformer Prodigy is a sophisticated AI training framework designed for Super Mario Bros, utilizing reinforcement learning techniques. The project leverages Python, PyTorch, and OpenAI Gym to create, train, and evaluate AI agents within a dynamic game environment.

## Features
* Advanced reinforcement learning algorithms like PPO and DQN for optimal AI performance.
* Realistic game environment simulation for comprehensive AI training.
* Detailed performance analysis and tuning.
* Preprocessing steps such as frame stacking and grayscaling to reduce the model training duration.

## Installation
1. Clone the repository or download the source code.
```bash
git clone https://github.com/silentwraith03/ai-platformer-prodigy.git
```
2. Navigate to the project directory
```bash
cd AI-Platformer-Prodigy
```
3. Install dependencies
```bash
pip install -r requirements.txt
pip install gym_super_mario_bros==7.3.0 nes_py
pip install torch==1.10.1+cu113 torchvision==0.11.2+cu113 torchaudio===0.10.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html
pip install stable-baselines3[extra]
```
4. Run
Ensure you have Jupyter Notebook installed. If not, you can install it using pip:
```bash
pip install jupyter
jupyter notebook
```
5. Visualize Training Progress
Use TensorBoard to visualize the training progress
```bash
cd logs
cd PPO
tensorboard --logdir=.
```

## Screenshots
<img src='images/sc1.png'>
<img src='images/sc2.png'>

## Demo
<img src='images/sc3.gif'>

## Tech Used
Frontend: Simulation environment visualization using Matplotlib and Pygame  
Backend: Python, PyTorch  
Simulation Environment: gym, gym_super_mario_bros    
Reinforcement Learning: stable-baselines3  
Data Handling: NumPy, Pandas  

## License
[MIT](LICENSE)



