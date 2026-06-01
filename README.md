# Constrained-Maxmin-MORL

Implementation for the ICML 2026 paper: "Constrained Multi-Objective Reinforcement Learning with Max-Min Criterion"

## Contact

If you have any question or discussion, feel free to send an e-mail to giseung.park@utoronto.ca.

Author's webpage: https://sites.google.com/view/giseung-park

## Installation

```
conda env create -f constrained_maxmin_mo_env.yaml
conda activate constrained_maxmin_mo_env
```

## Note

- The wandb logging code is commented out by default. If you want to use wandb for logging, uncomment the wandb-related lines in `maxmin_algorithms.py` and `stable_baselines3/dqn/dqn.py`.
- If installation fails, you can first install torch separately, remove the conda environment, and then reinstall it.

## Run

```
python maxmin_algorithms.py --galg gradnet --se 0
```

We used five random seeds: 0-4.

## Citation

```
@inproceedings{
  title={Constrained Multi-Objective Reinforcement Learning with Max-Min Criterion},
  author={Giseung Park*, Hyunyoung Nam*, Woohyeon Byeon, Amir Leshem, Youngchul Sung},
  booktitle={Forty-third International Conference on Machine Learning},
  year={2026}
}
```
