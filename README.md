# Reinforcement Learning Lab — HalfCheetah

  <a href="https://colab.research.google.com/github/alokshah04/pgss-L4R-RL-public/blob/main/student_rl.ipynb" 
  target="_parent">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>


PPO homework for PGSS. Students implement Proximal Policy Optimization from scratch
and train a MuJoCo HalfCheetah to run using only environment rewards — no expert demonstrations.

## Files

| File | Description |
|------|-------------|
| `student_rl.ipynb` | Student notebook — key PPO components blanked out for students to implement |
| `requirements.txt` | Python dependencies |

## Setup (local)

```bash
conda create -n il-lab python=3.11 -y
conda activate il-lab
pip install -r requirements.txt
jupyter notebook student_rl.ipynb
```

## Running on Colab

Open `student_rl.ipynb` in Colab, switch to a T4 GPU runtime, and run Step 0 first.
Video recording cells are local-only and should be skipped on Colab.
