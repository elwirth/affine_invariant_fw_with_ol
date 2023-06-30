# Affine-invariant FW

This repository is built on the [open-loop FW repository](https://github.com/ZIB-IOL/open_loop_fw).

## Installation guide

Download the repository and store it in your preferred location, say ~/tmp.

Open your terminal and navigate to ~/tmp.

Run the command:
```shell script
$ conda env create --file environment.yml
```

This will create the conda environment affine_invariant_fw.

Activate the conda environment with:
```shell script
$ conda activate affine_invariant_fw
```
Navigate to ~/tmp

Execute the experiments:
```python3 script
>>> python3 -m experiments.afw_difw_experiments
```
```python3 script
>>> python3 -m experiments.kernel_herding
```
```python3 script
>>> python3 -m experiments.locally_accelerated_convergence_rate_experiments
```
```python3 script
>>> python3 -m experiments.non_polytope_boundary_experiments
```
```python3 script
>>> python3 -m experiments.non_polytope_exterior_experiments
```
```python3 script
>>> python3 -m experiments.non_polytope_interior_experiments
```
```python3 script
>>> python3 -m experiments.polytope_experiments
```

The experiments are then stored in ~/tmp/experiments/figures.