# maml-dqn-satellite-tasking
AI - Project - MAML DQN satellite tasking. Transfer from Low Earth Orbit to Lunar Orbit with Few-shot learning

Code and artifacts for **"Rapid Adaptation of Satellite Tasking Policies from LEO to Lunar Orbit using Deep Q-Networks and Model-Agnostic Meta-Learning"** (SGAI submission).

## Repro quickstart
```bash
conda env create -f environment.yml
conda activate maml-dqn-sat

# Basilisk (https://github.com/AVSLab/basilisk)
"https://github.com/AVSLab/basilisk"
"https://github.com/AVSLab/bsk_rl"

# Run meta-training and adaptation
bash scripts/run_leo_meta_training.sh
bash scripts/run_lunar_adaptation.sh
