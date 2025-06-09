# Kinematic Analysis of 6 DOF Anthropomorphic Robotic Manipulators Based on the Jacobian Matrix Approach

This is the official repository for the paper:  
**Comparative Kinematic Analysis of 6 DOF Anthropomorphic Robotic Manipulators Based on the Jacobian Matrix Approach**.

The project analyzes various 6-DOF anthropomorphic robotic manipulators using the Jacobian matrix method. It includes velocity propagation, singularity detection, and manipulability index evaluation.

---

## How to run the code

We have provided two ways of running the code:
1. Online through Google Colab Notebooks.
2. Setting up local environment using the `requirements.txt` file and run either the notebooks or the scripts from the repository.

---

## 🔗 Online Mode: Google Colab Notebooks

Explore the interactive Colab notebooks for different manipulators:

- [Yaskawa GP7](https://colab.research.google.com/drive/1QkVSymcrz_CmqC4h9nBPZJVdNj4YdeDQ?usp=sharing)
- [FANUC LR Mate 200iD/7](https://colab.research.google.com/drive/1LWlLA-jX50K5EglNOTtiimfCcW-pyWmN?usp=sharing)
- [PUMA 560](https://colab.research.google.com/drive/1EAKLzmlFlaRKHM1JvbAqwKrU733uV1Zo?usp=sharing)
- [ABB IRB 140-6-0.8](https://colab.research.google.com/drive/1Pocf-Or8RYKdIAnjkk5VX_O7oNrjRtoP?usp=sharing)

> _Click on a link to launch and run the notebook in Google Colab._

---

## 🧑‍💻 Local Development: Notebooks and Scripts

For local use or further development, equivalent Python notebooks and scripts are available in the `notebooks/` and the `scripts/` directory respectively:

- `yaskawa_gp7.py`
- `fanuc_lr_mate_200id7.py`
- `puma_560.py`
- `abb_irb140.py`

**Install required dependencies using:**

```bash
pip install -r requirements.txt
