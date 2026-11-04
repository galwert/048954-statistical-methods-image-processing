# Statistical Methods in Image Processing (EE 048954)

Three graduate assignments on generative modelling, each a self-contained,
executed Jupyter notebook with derivations, implementation and results.

| Notebook | Topics |
|---|---|
| `HW1/submission/ee048954_hw1_id1_id2.ipynb` | Kernel density estimation, normalizing flows (affine coupling / RealNVP-style), likelihood evaluation |
| `HW2/ee048954_hw2.ipynb` | Langevin dynamics sampling, energy-based models trained with contrastive divergence, denoising noisy digits |
| `HW3/ee048954_hw3.ipynb` | Score matching, denoising score matching, annealed Langevin sampling |

All notebooks run on a single GPU with PyTorch, NumPy and Matplotlib. Model
checkpoints and intermediate tensors are not tracked.
