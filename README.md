# VAD-LLM

### 🔥🔥🔥[Quo Vadis, Anomaly Detection? LLMs and VLMs in the Spotlight](https://arxiv.org/abs/2412.18298)💡

---
## Comparison of recent methods in video anomaly detection (VAD)
We compare recent approaches in VAD, highlighting key aspects such as interpretability, temporal modeling, few-shot learning, and open-world detection. Performance
is evaluated across six benchmark datasets: UCSD Ped2 (Ped2) [45], CUHK Avenue (CUHK) [46], ShanghaiTech (ShT) [47], UCF-Crime (UCF) [12], XD-Violence (XD) [13], and UBnormal (UB) [14]. Datasets evaluated using Area Under the Curve (AUC) include Ped2, CUHK, ShT, UCF, and UB, while the XD dataset is evaluated using Average Precision (AP).
| Method            | LLM/VLM           | Interpret. | Temporal | Few-shot | Open-world | [Ped2](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)   | [CUHK](https://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html)   | [ShT](https://github.com/desenzhou/ShanghaiTechDataset)    | [UCF](https://www.crcv.ucf.edu/research/real-world-anomaly-detection-in-surveillance-videos/)    | [XD](https://roc-ng.github.io/XD-Violence/)     | [UB](https://github.com/lilygeorgescu/UBnormal/)     |
|--------------------|-------------------|------------|----------|----------|------------|--------|--------|--------|--------|--------|--------|
| [VLAVAD](https://arxiv.org/abs/2409.14109)       | Fine-tuning       | ✓          | ✓        |          |            | 99.0   | 87.6   | 87.2   | --     | --     | --     |
| [VADor](https://arxiv.org/abs/2401.05702)        | Fine-tuning       | ✓          | ✓        |          |            | --     | --     | --     | 88.1   | --     | --     |
| [OVVAD](https://arxiv.org/abs/2311.07042)        | Fine-tuning       |            | ✓        |          | ✓          | --     | --     | --     | 86.4   | 66.5   | 62.9   |
| [LAVAD](https://arxiv.org/abs/2404.01014)        | Training-free     | ✓          | ✓        | ✓        |            | --     | --     | --     | 80.3   | 62.0   | --     |
| [TPWNG](https://arxiv.org/abs/2404.08531)        | Fine-tuning       |            | ✓        |          |            | --     | --     | --     | 87.8   | 83.7   | --     |
| [Holmes-VAD](https://arxiv.org/abs/2406.12235)   | Fine-tuning       | ✓          | ✓        |          |            | --     | --     | --     | 89.5   | 90.7   | --     |
| [AnomalyRuler](https://arxiv.org/abs/2407.10299) | Fine-tuning       |            |          | ✓        |            | 97.9   | 89.7   | 85.2   | --     | --     | 71.9   |
| [STPrompt](https://arxiv.org/abs/2408.05905)     | Fine-tuning       | ✓          | ✓        |          |            | --     | --     | 97.8   | 88.1   | --     | 64.0   |
| [Holmes-VAU](https://arxiv.org/abs/2412.06171)   | Fine-tuning       |            | ✓        |          | ✓          | --     | --     | --     | 89.0   | 87.7   | --     |
| [VERA](https://arxiv.org/abs/2412.01095)         | Training-free     | ✓          |          |          |            | --     | --     | --     | 86.6   | 88.2   | --     |


