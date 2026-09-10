# Transformer 知识地图

## 00. Transformer 前置基础

### 00.1 数学

- 标量
- 向量
- 矩阵
- 张量
- 点积
- 矩阵乘法
- Transpose
- Softmax
- 指数
- 概率分布

### 00.2 深度学习

- Neural Network
- Layer
- Parameter
- Weight
- Bias
- Forward
- Loss
- Gradient
- Backpropagation

### 00.3 Tensor

- Shape
- Rank
- Batch
- Sequence Length
- Hidden Dimension
- Head Dimension
- Tensor Layout
- Reshape
- Transpose
- Permute
- View
- Contiguous

## 01. 为什么出现 Transformer

- Sequence
- Sequential Data
- RNN
- LSTM
- GRU
- Sequential Processing
- Long-term Dependency
- Vanishing Gradient
- Parallel Training
- Attention
- Transformer

## 02. Token

- Token
- Tokenization
- Vocabulary
- Token ID
- Sequence
- Sequence Length

### Special Token

- BOS
- EOS
- PAD
- UNK

- Word-level Tokenization
- Character-level Tokenization
- Subword Tokenization
- BPE
- WordPiece
- SentencePiece
- Vocabulary Size

## 03. Embedding

- Embedding
- Token Embedding
- Embedding Matrix
- Token ID
- Embedding Lookup
- Embedding Dimension
- Hidden Dimension
- Embedding Output Shape

## 04. Position

- 为什么需要位置信息
- Position Information
- Positional Encoding
- Sinusoidal Encoding
- Learned Positional Embedding
- Relative Position
- Absolute Position
- RoPE
- Rotary Embedding
- ALiBi
- Position Interpolation
- Long Context

## 05. Attention 基础

- Attention
- Query
- Key
- Value
- Q
- K
- V
- Attention Score
- Attention Weight
- Attention Output

## 06. Scaled Dot-Product Attention

### 06.1 Q

- Q 的含义
- Q 的来源
- Q Shape
- Q Projection

### 06.2 K

- K 的含义
- K 的来源
- K Shape
- K Projection

### 06.3 V

- V 的含义
- V 的来源
- V Shape
- V Projection

### 06.4 QKᵀ

- Matrix Multiplication
- Dot Product
- Shape 推导
- Attention Score Matrix
- Token-to-token Relationship

### 06.5 Scaling

- √d
- Head Dimension
- 为什么需要 Scaling
- 数值稳定性

### 06.6 Mask

- Attention Mask
- Padding Mask
- Causal Mask
- Upper Triangular Mask
- Mask Value

### 06.7 Softmax

- Softmax Input
- Softmax Output
- Probability Distribution
- Numerical Stability
- Max Subtraction

### 06.8 Attention Output

- Attention Weight × V
- Matrix Multiplication
- Shape 推导
- Output

## 07. Self-Attention

- Self-Attention
- Input → Q
- Input → K
- Input → V
- Token-to-token Attention
- Attention Matrix
- Causal Self-Attention
- Bidirectional Attention
- Masked Self-Attention

## 08. Multi-Head Attention

- Multi-Head
- Head
- Head Dimension
- Number of Heads
- Q Projection
- K Projection
- V Projection
- QKV Split
- Head Reshape
- Head Transpose
- Parallel Attention
- Head Concatenation
- Output Projection
- MHA

## 09. Attention 变体

### MHA

- Query Heads
- Key Heads
- Value Heads

### MQA

- Multi Query
- Shared K/V

### GQA

- Query Groups
- Shared K/V
- Group Size

- Local Attention
- Sliding Window Attention
- Sparse Attention
- Global Attention
- FlashAttention

## 10. Feed Forward Network

- FFN
- Linear Layer
- Hidden Dimension
- Intermediate Dimension
- Activation
- GELU
- ReLU
- SiLU
- SwiGLU
- Gated FFN
- Up Projection
- Down Projection
- FFN Parameter Count

## 11. Normalization

### LayerNorm

- Mean
- Variance
- Gamma
- Beta

- RMSNorm
- Pre-Norm
- Post-Norm
- Norm 的位置

## 12. Residual Connection

- Residual
- Skip Connection
- Identity Mapping
- Gradient Flow
- Attention Residual
- FFN Residual

## 13. Transformer Block

- Transformer Block
- Attention
- Residual
- Normalization
- FFN
- Pre-Norm Block
- Post-Norm Block
- Input Shape
- Intermediate Shape
- Output Shape

## 14. Encoder

- Encoder
- Encoder Layer
- Self-Attention
- FFN
- Residual
- LayerNorm
- Encoder Stack
- Encoder Output

## 15. Decoder

- Decoder
- Masked Self-Attention
- Cross-Attention
- FFN
- Residual
- LayerNorm
- Decoder Layer
- Decoder Stack

## 16. Cross Attention

- Query 来源
- Key 来源
- Value 来源
- Encoder-Decoder Attention
- Q Shape
- K Shape
- V Shape
- Attention Score
- Cross Attention Output

## 17. Transformer 整体数据流

- Token
- Token ID
- Embedding
- Position
- Transformer Block
- Attention
- FFN
- Residual
- Normalization
- Layer Stack
- Final Norm
- Linear
- Logits
- Softmax

## 18. Transformer Shape 推导

- Batch Size
- Sequence Length
- Hidden Size
- Number of Heads
- Head Dimension
- Q Shape
- K Shape
- V Shape
- Attention Score Shape
- Attention Output Shape
- FFN Input Shape
- FFN Intermediate Shape
- FFN Output Shape

## 19. Transformer 训练

- Language Modeling
- Next Token Prediction
- Teacher Forcing
- Causal Language Model
- Masked Language Model
- Cross Entropy
- Logits
- Label
- Loss
- Backpropagation
- Gradient
- Optimizer
- Learning Rate
- Warmup
- Weight Decay
- Gradient Clipping

## 20. Transformer 经典架构

- Original Transformer
- BERT
- GPT
- GPT-style Decoder
- T5
- ViT
- Swin Transformer
- Encoder-only / Decoder-only / Encoder-Decoder

## 21. LLM

- Large Language Model
- Decoder-only
- Causal LM
- Pretraining
- Instruction Tuning
- SFT
- RLHF
- DPO
- Context Window
- Context Length
- Parameter Count
- Model Size
- Scaling
- Scaling Law

## 22. LLM 推理

- Autoregressive Generation
- Prompt
- Input Tokens
- Output Tokens
- Logits
- Sampling
- Greedy Decoding
- Temperature
- Top-K
- Top-P
- Repetition Penalty
- Prefill
- Decode
- First Token Latency
- Inter-token Latency
- Tokens/s

## 23. KV Cache

- 为什么需要 KV Cache
- K Cache
- V Cache
- Cache Initialization
- Cache Update
- Cache Read
- Cache Shape
- Cache Layout
- Cache Memory
- Cache Growth
- MHA KV Cache
- MQA KV Cache
- GQA KV Cache
- KV Cache Quantization
- KV Cache Compression

## 24. Prefill

- Prefill 阶段
- 输入完整 Sequence
- Attention
- QKV
- KV Cache 写入
- Parallelism
- Compute Intensity
- Matrix Multiplication
- Prefill Latency

## 25. Decode

- Decode 阶段
- 单 Token 输入
- KV Cache Read
- Q
- K Cache
- V Cache
- Attention
- Memory Bandwidth
- Memory Bound
- Decode Latency

## 26. Transformer 算子

- Linear
- MatMul
- BatchMatMul
- GEMM
- GEMV
- Softmax
- Add
- Mul
- Div
- Exp
- Sqrt
- Reduce
- RMSNorm
- LayerNorm
- RoPE
- Transpose
- Reshape
- Split
- Concat
- Gather
- Scatter
- Cache Read
- Cache Write
- Attention

## 27. Attention 算子拆解

- Q Projection
- K Projection
- V Projection
- QKᵀ
- Scale
- Mask
- Softmax
- Softmax × V
- Output Projection
- Fusion

## 28. Transformer 性能

- Parameter Count
- Model Size
- FLOPs
- MACs
- Attention Complexity
- Sequence Length Complexity
- O(n²)
- Memory Complexity
- KV Cache Memory
- Memory Bandwidth
- Compute Bound
- Memory Bound
- Arithmetic Intensity
- Prefill Performance
- Decode Performance
- Throughput

## 29. Attention 优化

- FlashAttention
- Tiling
- Blocking
- IO-aware Attention
- Memory Hierarchy
- SRAM
- DRAM
- On-chip Memory
- MHA
- MQA
- GQA
- Sliding Window
- Sparse Attention

## 30. Transformer 模型优化

- Quantization
- Pruning
- Distillation
- Low-rank Approximation
- LoRA
- Weight Sharing
- KV Cache Optimization
- Operator Fusion
- Graph Optimization
- Memory Optimization

## 31. Transformer 量化

- FP32
- FP16
- BF16
- INT8
- INT4
- FP8
- PTQ
- QAT
- Weight Quantization
- Activation Quantization
- KV Cache Quantization
- Weight-only Quantization
- Per-tensor
- Per-channel
- Per-group
- Symmetric
- Asymmetric
- Scale
- Zero Point
- Calibration
- Quantization Error

## 32. Transformer 推理优化

- KV Cache
- Continuous Batching
- Paged KV Cache
- Prefix Cache
- Speculative Decoding
- Tensor Parallelism
- Pipeline Parallelism
- Sequence Parallelism
- Batch Scheduling
- Memory Management

## 33. Transformer 端侧部署

### Model Export

- PyTorch
- ONNX
- TorchScript
- Other IR

- Model Conversion

### Graph

- Computational Graph
- Tensor
- Operator
- Node
- Edge

### Graph Optimization

- Constant Folding
- Dead Node Elimination
- Operator Fusion
- Layout Transformation
- Memory Planning
- Graph Rewrite

### Operator Support

- MatMul
- Softmax
- RMSNorm
- RoPE
- Attention
- KV Cache

### Hardware Partition

- CPU
- GPU
- NPU
- Heterogeneous Execution

### Compilation

- Lowering
- Graph Lowering
- Operator Lowering
- Kernel Selection
- Scheduling
- Code Generation
- Memory Planning
- Hardware-specific Compilation

### Runtime

- Model Loading
- Tensor Allocation
- KV Cache Allocation
- Memory Management
- Execution
- Synchronization
- Device Management

### NPU

- NPU Architecture
- NPU Compute
- NPU Memory
- NPU Kernel
- NPU Compiler
- NPU Runtime
- NPU-specific Operator
