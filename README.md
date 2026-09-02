# Multimodal-Depression-Detection

## Abstract

> The source code is accessible at https://github.com/Rafi3690/Multimodal-Depression-Detection.

---

## Architecture

<p align="center">
  <img src="figures/proposed_method.png"
       alt="Overview of the proposed multimodal depression detection framework."
       width="600">
</p>


<!--
```python
Version : 0.0.1
Author  : M.A. Rafi
Email   : 190125.cse@student.just.edu.bd
```
-->

---

**LOCAL ENVIRONMENT**

```text
OS: Windows 11
Memory: 64 GB
Processor: AMD Ryzen 9 3900X
CPU: 12 Cores / 24 Threads
Graphics: NVIDIA GeForce RTX 3090
GPU Memory: 24 GB
```

---

### Prepare Datasets

<p align="center">
  <img src="figures/multimodal_dataset_block_diagram.png"
       alt="Block diagram of the multimodal dataset and corresponding data modalities"
       width="900">
</p>

**Figure 2.** Block diagram illustrating the multimodal dataset and the corresponding data modalities used for depression detection.

We use the [D-Vlog](https://doi.org/10.1609/aaai.v36i11.21483) dataset, proposed in this paper. For the D-Vlog dataset, please fill in the form at the bottom of the [dataset website](https://sites.google.com/view/jeewoo-yoon/dataset), and send a request email to the [author](mailto:yoonjeewoo@gmail.com).

Following D-Vlog's setup, the dataset is split into train, validation, and test sets with a 7:1:2 ratio.

---

### Python Requirements

---

### Execution (Depression Detection)

Activate your conda environment:

```bash
conda activate your_env
```
