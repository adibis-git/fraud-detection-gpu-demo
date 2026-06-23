# ⚡ GPU-Accelerated Fraud Detection Demo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adibis-git/fraud-detection-gpu-demo/blob/main/fraud_detection_gpu_demo.ipynb)

A live, runnable benchmark showing **CPU vs GPU inference speed** for financial fraud detection using XGBoost and the PaySim dataset (6.36M transactions).

**Click the badge above → change runtime to T4 GPU → Run All. Done in ~10 minutes.**

## What you'll see

- Real transaction data loaded from Hugging Face (no Kaggle login, no manual downloads)
- XGBoost fraud model trained and evaluated (AUC-ROC > 0.99)
- Side-by-side throughput and latency benchmark: CPU vs GPU
- Cost-per-million-inference estimate using AWS on-demand pricing

## Why this matters in BFSI

Real-time card authorisation has a ~200ms window. At peak volumes — festive sales, IPO days — CPU-based inference creates queues. GPU inference absorbs the burst within SLA and costs less per inference at scale.

---

<!-- LinkedIn post template
🚨 Live demo: GPU-accelerated fraud detection — click and run it yourself in 10 min.

Built a notebook that scores 1.27M financial transactions on CPU vs GPU and shows you the throughput gap in a single chart.

▶️ [Colab link]

If you're in BFSI and your fraud model runs on CPU, let's talk about what the switch actually looks like.

#BFSI #FraudDetection #MachineLearning #GPU #FinTech
-->
