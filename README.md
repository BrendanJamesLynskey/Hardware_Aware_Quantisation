## Hardware-Aware Quantisation Explorer

Interactive hardware-aware quantisation explorer — visualise how neural network weights map to fixed-point and low-bit formats, with simulated inference accuracy and hardware cost.

### [Launch App](https://brendanjameslynskey.github.io/Hardware_Aware_Quantisation/)

---

### Features

- **Number Format Explorer**: Visualise bit layouts for FP32, FP16, BF16, FP8, INT8, INT4, and NF4 with interactive bit-level inspection.
- **Weight Distribution Visualiser**: Generate synthetic weight distributions, quantise them, and see the error introduced.
- **Quantisation Schemes**: Compare symmetric/asymmetric, per-tensor/per-channel/per-group, and calibration methods.
- **Simulated Inference**: Train a toy MLP on a 2D classification task and observe decision boundary degradation under quantisation.
- **Hardware Cost Model**: Compare multiplier area, SRAM usage, and memory bandwidth across formats.
- **Mixed-Precision Explorer**: Assign per-layer precision and see the accuracy-size tradeoff.

