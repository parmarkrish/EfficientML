# EfficientML
My lab solutions to MIT's [EfficientML course](https://hanlab.mit.edu/courses/2023-fall-65940).

## [Lab 1: Pruning](https://github.com/parmarkrish/EfficientML/blob/main/Lab1.ipynb)
- Fine-grained pruning
- Sensitivity scanning (finding per layer pruning ratio)
- Channel pruning with ConvNets

## [Lab 2: Quantization](https://github.com/parmarkrish/EfficientML/blob/main/Lab2.ipynb)
- K-means quantization
- Quantization-aware training (QAT) with k-means quantization
- Linear quantization for simulated integer-only arithmetic (QuantizedLinear and QuantizedConv) 

## [Lab 3: Neural Architecture Search](https://github.com/parmarkrish/EfficientML/blob/main/Lab3.ipynb)
- NAS following [Once for all paper](https://arxiv.org/abs/1908.09791)
- Efficiency and accuracy predictors
- Evolutionary search agent (mutations and cross-overs of population of sub-nets)

## [Lab 4: LLM Quantization with AWQ](https://github.com/parmarkrish/EfficientML/blob/main/Lab4.ipynb)
- Scaffolded implementation of [Activation Aware Weight Quantization (AWQ)](https://arxiv.org/abs/2306.00978)
- Weights quantized to 4-bit and activation to 16-bit
- Automated finding of optimal scale factor (a hyperparameter in AWQ)

## Lab 5: Optimize LLMs on Edge
*Not completed yet as I need to understand loop unrolling first :/*