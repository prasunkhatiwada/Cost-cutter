Tesla T4 LLM Quantization Benchmark

My experiment comparing FP16 and AWQ 4-bit quantization for LLM inference using NVIDIA Tesla T4.

Hardware
GPU: NVIDIA Tesla T4
VRAM: 15 GB
CUDA: 13.0
Software
vLLM: 0.33.0
PyTorch: 2.14.1+cu130
Python: 3.13
Model

Qwen2.5-1.5B-Instruct

Experiment

Comparing:

FP16 inference
AWQ 4-bit inference

Metrics:

GPU memory consumption
Tokens per second
Model loading time
Inference latency
Initial Results
AWQ model loaded successfully.
AWQ text generation successful.
Initial generation speed: 10.56 tokens/sec.
FP16 initialization issue under investigation.
Project Status

In progress 🚀

Objective

Explore efficient LLM deployment and quantization on consumer and cloud GPUs.
