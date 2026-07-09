# Reinforcement Learning Lab — HalfCheetah

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
