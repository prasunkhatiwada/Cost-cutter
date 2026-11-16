FP16 vs AWQ Benchmark Results
Hardware
GPU: NVIDIA Tesla T4 (15 GB)
CUDA: 13.0
PyTorch: 2.14.1
vLLM: 0.33.0
Model Comparison
Metric	FP16	AWQ
Model	Qwen2.5-1.5B-Instruct	Qwen2.5-1.5B-Instruct-AWQ
Precision	FP16	4-bit AWQ
Model loading	Failed during engine initialization	Successful
Inference	Not completed	Successful
Output speed	Not available	10.56 tokens/sec
Conclusion

AWQ quantization successfully enabled model inference on the Tesla T4 GPU. FP16 encountered an engine initialization error and requires further debugging.

Key Learning

Quantization reduces model weight precision and can improve memory efficiency, making LLM deployment more practical on limited GPU hardware.
