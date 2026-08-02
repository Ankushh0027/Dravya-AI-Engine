# Dravya AI

Dravya AI is an enterprise-grade artificial intelligence engine designed for robust data processing, model training, evaluation, and real-time inference. Built with modularity, scalability, and production readiness in mind, the platform provides end-to-end capabilities from raw data auditing to API serving.

## Project Status
* **Current Status:** Foundation / Phase 1
* **Python Version:** 3.12

## Directory Structure

```
Dravya-AI-Engine/
├── src/
│   ├── __init__.py
│   ├── audit/
│   ├── data/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   ├── inference/
│   ├── api/
│   └── utils/
├── datasets/
│   ├── raw/
│   ├── processed/
│   └── final/
├── models/
├── configs/
├── notebooks/
├── reports/
├── tests/
└── docs/
```

## Deep Learning Environment

* **Python Version:** 3.12.10
* **PyTorch Stack:** `torch==2.13.0+cpu`, `torchvision==0.28.0+cpu`
* **Hardware Acceleration:** CPU-only (the current development machine contains no NVIDIA CUDA GPU)
* **Future GPU Training:** Future GPU training or cloud deployment can utilize a separate compatible CUDA environment without changing application code.
