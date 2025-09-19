# Paper-Notes

This repository contains my personal notes on papers, combining summaries, explanations, detailed notes, and slide presentations (PPT), along with links to the original papers and related GitHub repositories. Suitable for self-study or as a reference for others.

### **Agent**

### **KV Cache**
*   **Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free** [NeurIPS'26 Oral] [[paper]](https://arxiv.org/abs/2505.06708) [[github]](https://github.com/qiuzh20/gated_attention)
*   **MagicPIG: LSH Sampling for Efficient LLM Generation** [ICLR'25 Spotlight] [[paper]](https://arxiv.org/abs/2410.16179) [[github]](https://github.com/Infini-AI-Lab/MagicPIG)
*   **APE - Faster and Longer Context-Augmented Generation via Adaptive Parallel Encoding** [ICLR'25] [[paper]](https://arxiv.org/abs/2502.05431) [[github]](https://github.com/Infini-AI-Lab/APE)
*   **CAKE: Cascading and Adaptive KV Cache Eviction with Layer Preferences** [ICLR'25] [[paper]](https://arxiv.org/html/2503.12491) [[github]](https://github.com/antgroup/cakekv)
*   **CacheBlend - Fast Large Language Model Serving for RAGwithCached Knowledge Fusion** [Eurosys'25] [[paper]](https://arxiv.org/abs/2405.16444) 
*   **ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference** [ICML'25 Spotlight] [[paper]](https://arxiv.org/pdf/2410.21465.pdf) [[github]](https://github.com/bytedance/ShadowKV)
*   **HashAttention - Semantic Sparsity for Faster Inference** [ICML'25] [[paper]](https://arxiv.org/abs/2412.14468) [[github]](https://github.com/xAlg-ai/HashAttention-1.0)
*   **MMInference: Accelerating Pre-filling for Long-Context VLMs via Modality-Aware Permutation Sparse Attention** [ICML'25] [[paper]](https://arxiv.org/abs/2504.16083) [[github]](https://github.com/microsoft/MInference)
*   **XAttention - Block Sparse Attention with Antidiagonal Scoring** [ICML'25] [[paper]](https://arxiv.org/abs/2503.16428) [[github]](https://github.com/mit-han-lab/x-attention)
*   **CacheGen: Fast Context Loading for Language Model Applications via KV Cache Streaming** [SIGCOMM'24] [[paper]](https://arxiv.org/pdf/2310.07240.pdf) [[github]](https://github.com/UChi-JCL/CacheGen)
*   **TriForce: Lossless Acceleration of Long Sequence Generation with Hierarchical Speculative Decoding** [COLM'24] [[paper]](https://arxiv.org/abs/2404.11912) [[github]](https://github.com/Infini-AI-Lab/TriForce)
*   **MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention** [NeurIPS'24 Spotlight, ICLR'25] [[paper]](https://arxiv.org/abs/2405.03456) [[github]](https://github.com/microsoft/MInference)
*   **Efficient Streaming Language Models with Attention Sinks** [ICLR'24] [[paper]](http://arxiv.org/abs/2309.17453) [[github]](https://github.com/mit-han-lab/streaming-llm)


### **MLLM**
*   **CoreMatching - Co-adaptive Sparse Inference Framework for Comprehensive Acceleration of Vision Language Model** [ICML'25] [[paper]](https://arxiv.org/abs/2503.02175) [[github]](https://github.com/wangqinsi1/2025-ICML-CoreMatching)
*   **DivPrune - Diversity-based Visual Token Pruning for Large Multimodal Models** [CVPR'25] [[paper]](https://arxiv.org/abs/2405.19635) [[github]](https://github.com/vbdi/divprune)
*   **DyCoke - DynamicCompression of Tokens for Fast Video Large Language Models** [CVPR'25] [[paper]](https://arxiv.org/abs/2411.15024) [[github]](https://github.com/KD-TAO/DyCoke)
*   **VisionZip - Longer is Better but Not Necessary in Vision Language Models** [CVPR'25] [[paper]](https://arxiv.org/abs/2412.04467) [[github]](https://github.com/dvlab-research/VisionZip)
*   **TimeChat-Online - 80% Visual Tokens are Naturally Redundant in Streaming Videos** [MM'25] [[paper]](https://arxiv.org/abs/2504.17343) [[github]](https://github.com/yaolinli/TimeChat-Online)
*   **VoCo-LLaMA - Towards Vision Compression with Large Language Models** [ICLR'25] [[paper]](https://arxiv.org/abs/2406.12275v2) [[github]](https://github.com/Yxxxb/VoCo-LLaMA)
*   **γ-MOD - Exploring Mixture-of-Depth Adaptation for Multimodal Large Language Models** [ICLR'25] [[paper]](https://arxiv.org/abs/2410.13859) [[github]](https://github.com/Yaxin9Luo/Gamma-MOD)

### **Quantization**
*   **Optimizing Large Language Model Training Using FP4 Quantization** [ICML'25] [[paper]](https://arxiv.org/abs/2501.17116)
*   **ResQ - Mixed-Precision Quantization of Large Language Models with Low-Rank Residuals** [ICML'25] [[paper]](https://arxiv.org/abs/2412.14363) [[github]](https://github.com/utkarsh-dmx/project-resq)
*   **SVDQuant: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models** [ICLR'25 Spotlight] [[paper]](http://arxiv.org/abs/2411.05007) [[github]](https://github.com/nunchaku-tech/nunchaku)
*   **SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration** [ICLR'25] [[paper]](https://arxiv.org/abs/2410.02367) [[github]](https://github.com/thu-ml/SageAttention)
*   **SageAttention3 - Microscaling FP4 Attention for Inference and An Exploration of 8-Bit Training** [[paper]](https://arxiv.org/abs/2505.11594) [[github]](https://github.com/thu-ml/SageAttention)
*   **SliM-LLM - Salience-Driven Mixed-Precision Quantization for Large Language Models** [ICML'25] [[paper]](https://arxiv.org/abs/2405.14917) [[github]](https://github.com/Aaronhuang-778/SliM-LLM)
*   **SpinQuant: LLM Quantization with Learned Rotations** [ICLR'25] [[paper]](https://arxiv.org/pdf/2405.16406) [[github]](https://github.com/facebookresearch/SpinQuant)
*   **AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration** [MLSys'24 Best Paper] [[paper]](https://arxiv.org/abs/2306.00978) [[github]](https://github.com/mit-han-lab/llm-awq)
*   **SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models** [ICML'23] [[paper]](https://arxiv.org/abs/2211.10438) [[github]](https://github.com/mit-han-lab/smoothquant)


### **Recommendation System**

### **Speculative Decoding**
*   **EAGLE-3:Scaling up Inference Acceleration of Large Language Models via Training-Time Test**  [[paper]](https://arxiv.org/pdf/2503.01840) [[github]](https://github.com/SafeAILab/EAGLE)
*   **MAGICDEC - Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding** [ICLR'25] [[paper]](https://arxiv.org/abs/2408.11049) [[github]](https://github.com/Infini-AI-Lab/MagicDec/)
*   **PEARL - Parallel Speculative Decoding with Adaptive Draft Length** [ICLR'25] [[paper]](https://arxiv.org/abs/2408.11850)
*   **EAGLE: Speculative Sampling Requires Rethinking Feature Uncertainty** [ICML'24] [[paper]](https://arxiv.org/pdf/2401.15077) [[github]](https://github.com/SafeAILab/EAGLE)
*   **EAGLE-2: Faster Inference of Language Models with Dynamic Draft Trees** [EMNLP'24] [[paper]](https://arxiv.org/pdf/2406.16858) [[github]](https://github.com/SafeAILab/EAGLE)

### **System**
*   **NEO - Saving GPU Memory Crisis with CPU Offloading for Online LLM Inference** [MLsys'25] [[paper]](https://arxiv.org/abs/2411.01142) [[github]](https://github.com/NEO-MLSys25/NEO)
*   **T-MAC - A Transport Protocol for Remote-Memory-Access-based LLM Inference** [EuroSys'25] [[paper]](https://arxiv.org/abs/2407.00088) [[github]](https://github.com/microsoft/T-MAC)
*   **Parrot: Efficient Serving of LLM-based Application with Semantic Variable** [OSDI'24] [[paper]](https://www.usenix.org/system/files/osdi24-lin-chaofan.pdf) [[github]](https://github.com/microsoft/ParrotServe)
*   **FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU** [ICML'23] [[paper]](https://arxiv.org/abs/2303.06865) [[github]](https://github.com/FMInference/FlexGen)


### **Technical Report**
*   **Llama 4** [[blog]](https://ai.meta.com/blog/llama-4-multimodal-intelligence/)
