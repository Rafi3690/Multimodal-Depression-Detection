# Multimodal-Depression-Detection

## Abstract

> The source code is accessible at https://github.com/Rafi3690/Multimodal-Depression-Detection.

---

## Architecture

<p align="center">
  <img src="https://drive.google.com/file/d/1GWORFJFk62-_YcMikqnIenZVkE4tL-cS/view?usp=sharing"
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
We developed the Categorized Multimodal Dataset for Depression Detection (CMDDD) by integrating text, image, and audio data from multiple public datasets. The final CMDDD contains **55,713 multimodal samples** categorized as **Highly Positive, Positive, Negative, and Neutral**. Text, image, and audio features were extracted using **BERT, ViT, and Wav2Vec2.0**, respectively. Unlabeled modality-specific data were categorized using **k-means clustering**, with distance-based refinement used to derive the Highly Positive category. The resulting modality-specific samples were then aligned by emotional category to construct the final multimodal dataset.
<p align="center">
  <img src="https://drive.google.com/file/d/1nqNo-JE9DaVBIDIcg5KxMYFYiHB5psxz/view?usp=sharing"
       alt="Block diagram of the multimodal dataset and corresponding data modalities."
       width="600">
</p>
---

### Python Requirements

---

### Execution (Depression Detection)

Activate your conda environment:

```bash
conda activate your_env
```
