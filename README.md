# Pruning for Large Language Models


I currently focus on pruning for large language models including
- [Surveys](#Surveys)
- [Unstructured Pruning](#Unstructured-Pruning)
- [Structured Pruning](#Structured-Pruning)
- [Semi-Structured Pruning](#Semi-Structured-Pruning)
  
<strong> Last Update: 2025/06/07 </strong>



<a name="Surveys" />

## Surveys 
- [2025] A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond, arXiv [[Paper](https://arxiv.org/pdf/2503.21614)] [[Code](https://github.com/XiaoYee/Awesome_Efficient_LRM_Reasoning)]
- [2025] A Survey on Efficient Vision-Language Models, arXiv [[Paper](https://arxiv.org/abs/2504.09724)]
- [2025] Distributed LLMs and Multimodal Large Language Models: A Survey on Advances, Challenges, and Future Directions, arXiv [[Paper](https://arxiv.org/abs/2503.16585)]
- [2024] A Survey on Model Compression for Large Language Models, TACL [[Paper](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00704/125482)] 
- [2024] Efficient Large Language Models: A Survey, TMLR [[Paper](https://arxiv.org/abs/2312.03863)] [[Code](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey)]
- [2024] A Survey of Large Language Models, arXiv [[Paper](https://arxiv.org/abs/2303.18223)] [[Code](https://github.com/RUCAIBox/LLMSurvey)]



<a name="Unstructured-Pruning" />

##  Unstructured Pruning
- [2025] Dynamic Superblock Pruning for Fast Learned Sparse Retrieval, SIGIR [[Paper](https://arxiv.org/abs/2504.17045)]  [[Code](https://github.com/thefxperson/hierarchical_pruning)]
- [2025] Two Sparse Matrices are Better than One: Sparsifying Neural Networks with Double Sparse Factorization, ICLR [[Paper](https://openreview.net/forum?id=DwiwOcK1B7)]  [[Code](https://github.com/usamec/double_sparse)]
- [2024] Fast and Effective Weight Update for Pruned Large Language Models, TMLR [[Paper](https://openreview.net/forum?id=1hcpXd9Jir)] [[Code](https://github.com/fmfi-compbio/admm-pruning)]
- [2024] A Simple and Effective Pruning Approach for Large Language Models, ICLR [[Paper](https://arxiv.org/abs/2306.11695)] [[Code](https://github.com/locuslab/wanda)]
- [2024] Pruner-Zero: Evolving Symbolic Pruning Metric From Scratch for Large Language Models, ICML [[Paper](https://openreview.net/forum?id=1tRLxQzdep)] 
- [2024] MaskLLM: Learnable Semi-Structured Sparsity for Large Language Models, NeurIPS [[Paper](https://arxiv.org/abs/2409.17481)] 
- [2024] Dynamic Sparse No Training: Training-Free Fine-tuning for Sparse LLMs, ICLR [[Paper](https://arxiv.org/abs/2310.08915)] 
- [2024] A Convex-optimization-based Layer-wise Post-training Pruner for Large Language Models, arXiv [[Paper](https://arxiv.org/abs/2408.03728)]
- [2023] SparseGPT: Massive Language Models Can be Accurately Pruned in One-Shot, ICML [[Paper](https://arxiv.org/abs/2301.00774)] [[Code](https://github.com/IST-DASLab/sparsegpt)]
- [2023] One-Shot Sensitivity-Aware Mixed Sparsity Pruning for Large Language Models, arXiv [[Paper](https://arxiv.org/pdf/2310.09499v1.pdf)]



<a name="structured-Pruning" />

## Structured Pruning
- [2025] SPAP: Structured Pruning via Alternating Optimization and Penalty Methods, arXiv [[Paper](https://arxiv.org/abs/2505.03373)] 
- [2025] Týr-the-Pruner: Unlocking Accurate 50% Structural Pruning for LLMs via Global Sparsity Distribution Optimization, arXiv [[Paper](https://arxiv.org/abs/2503.09657)] 
- [2025] Probe Pruning: Accelerating LLMs through Dynamic Pruning via Model-Probing, ICLR [[Paper](https://arxiv.org/abs/2502.15618)]
- [2025] Lightweight and Post-Training Structured Pruning for On-Device Large Lanaguage Models, arXiv [[Paper](https://arxiv.org/abs/2501.15255)]
- [2025] FASP: Fast and Accurate Structured Pruning of Large Language Models, arXiv [[Paper](https://arxiv.org/abs/2501.09412)]
- [2024] FinerCut: Finer-grained Interpretable Layer Pruning for Large Language Models, NeurIPS [[Paper](https://openreview.net/forum?id=jrSWzgno4W)] 
- [2024] Fluctuation-Based Adaptive Structured Pruning for Large Language Models, AAAI [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28960)]
- [2024] LoRAP: Transformer Sub-Layers Deserve Differentiated Structured Compression for Large Language Models, ICML [[Paper](https://arxiv.org/abs/2404.09695)][[Code](https://github.com/lihuang258/LoRAP)]
- [2024] SlimGPT: Layer-wise Structured Pruning for Large Language Models, NeurIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c1c44e46358e0fb94dc94ec495a7fb1a-Abstract-Conference.html)] 
- [2024] Sheared LLaMA: Accelerating Language Model Pre-training via Structured Pruning, NeurIPS [[Paper](https://openreview.net/forum?id=09iOdaeOzp)] 
- [2024] Everybody Prune Now: Structured Pruning of LLMs with only Forward Passes, arXiv [[Paper](https://arxiv.org/abs/2402.05406)] 
- [2024] Compact Language Models via Pruning and Knowledge Distillation, arXiv [[Paper](https://www.arxiv.org/abs/2407.14679)] 
- [2024] A Deeper Look at Depth Pruning of LLMs, ICML [[Paper](https://openreview.net/forum?id=9B7ayWclwN)] 
- [2024] Perplexed by Perplexity: Perplexity-Based Data Pruning With Small Reference Models, arXiv [[Paper](https://arxiv.org/abs/2405.20541)] 
- [2024] Plug-and-Play: An Efficient Post-training Pruning Method for Large Language Models, ICLR [[Paper](https://openreview.net/forum?id=Tr0lPx9woF)] 
- [2024] BESA: Pruning Large Language Models with Blockwise Parameter-Efficient Sparsity Allocation, arXiv [[Paper](https://arxiv.org/abs/2402.16880)]
- [2024] ShortGPT: Layers in Large Language Models are More Redundant Than You Expect, arXiv [[Paper](https://arxiv.org/abs/2403.03853)] 
- [2024] NutePrune: Efficient Progressive Pruning with Numerous Teachers for Large Language Models, arXiv [[Paper](https://arxiv.org/abs/2402.09773)] 
- [2024] SliceGPT: Compress Large Language Models by Deleting Rows and Columns, ICLR[[Paper](https://arxiv.org/abs/2401.15024)] [[Code](https://github.com/microsoft/TransformerCompression?utm_source=catalyzex.com)]
- [2023] LoRAShear: Efficient Large Language Model Structured Pruning and Knowledge Recovery, arXiv [[Paper](https://arxiv.org/abs/2310.18356)]
- [2023] LLM-Pruner: On the Structural Pruning of Large Language Models, NeurIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/44956951349095f74492a5471128a7e0-Abstract-Conference.html)] [[Code](https://github.com/horseee/LLM-Pruner)]
- [2023] Sheared LLaMA: Accelerating Language Model Pre-training via Structured Pruning, NeurIPS [[Paper](https://arxiv.org/abs/2310.06694)] [[Code](https://github.com/princeton-nlp/LLM-Shearing)]
- [2023] LoRAPrune: Pruning Meets Low-Rank Parameter-Efficient Fine-Tuning, arXiv [[Paper](https://doi.org/10.48550/arXiv.2305.18403)]
- [2023] LoSparse: Structured Compression of Large Language Models based on Low-Rank and Sparse Approximation, ICML [[Paper](https://proceedings.mlr.press/v202/li23ap.html)] [[Code](https://github.com/yxli2123/LoSparse)]

  

<a name="Semi-Structured-Pruning" />

## Semi-Structured Pruning
- [2025] Pruning Large Language Models with Semi-Structural Adaptive Sparse Training, AAAI [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/34592)] 
