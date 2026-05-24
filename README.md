# LLTNN

## Description

Matlab implementation for the paper:  
**"Hierarchical Progressive Transform with Learnable Prior for Hyperspectral Image Super-Resolution"**

- **Homepage:** [https://tuzhihui.github.io/](https://tuzhihui.github.io/)
- **Contact:** If you have any questions, please contact tuzh_2019@163.com

---

## File Structure

| File               | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| `Demo_SR_PU.m`     | **Main demo.** Runs the complete LLTNN method on the **Pavia University (PU)** dataset with the full Hierarchical Progressive Transform (HPT) module. |
| `Ablation_study.m` | **Ablation study.** Evaluates LLTNN **w/o HPT** (without the Hierarchical Progressive Transform) on the PU dataset to validate the contribution of the proposed transform. |
| `*.m`              | Other utility functions and core solvers.                    |

---

## Quick Start

### 1. Main Experiment — LLTNN (Full Model)

To reproduce the main result on the **Pavia University** dataset, directly run:

```matlab
Demo_SR_PU
```
