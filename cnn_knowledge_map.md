# CNN 知识地图

## 00. CNN 前置数学与深度学习基础

### 00.1 数学基础

- 标量
- 向量
- 矩阵
- 张量
- 矩阵乘法
- 向量点积
- Hadamard Product
- 求和
- 均值
- 方差
- 最大值
- 最小值
- 指数
- 对数
- 概率

### 00.2 深度学习基本概念

- 神经元
- 神经网络
- Layer
- Parameter
- Weight
- Bias
- Feature
- Feature Map
- Forward
- Loss
- Backward
- Gradient
- Optimization

### 00.3 Tensor 基础

- Tensor
- Shape
- Rank
- Dimension
- Batch
- Channel
- Height
- Width
- NCHW
- NHWC
- Tensor Layout
- Contiguous
- Stride
- Reshape
- Transpose
- Permute
- Flatten
- Unsqueeze
- Squeeze

## 01. 图像与 CNN

### 01.1 图像表示

- Pixel
- RGB
- Grayscale
- Channel
- Resolution
- Width
- Height

### 01.2 图像 Tensor

- 单张图片
- Batch 图片
- CHW
- HWC
- NCHW
- NHWC

### 01.3 CNN 为什么适合图像

- 局部连接
- 权重共享
- 局部特征
- 平移等变性
- 层级特征
- 空间信息
- 感受野

## 02. 卷积

### 02.1 卷积基本概念

- Convolution
- Kernel
- Filter
- Weight
- Bias
- Input
- Output
- Feature Map
- Sliding Window

### 02.2 一维卷积

- Input
- Kernel
- Sliding
- Dot Product
- Output

### 02.3 二维卷积

- Input Feature Map
- Kernel
- Window
- Element-wise Multiply
- Accumulation
- Output Feature Map

### 02.4 三维卷积

- 3D Kernel
- Depth
- Spatial Dimension
- 3D Feature Map

### 02.5 Conv Tensor Shape

- Input Shape
- Weight Shape
- Bias Shape
- Output Shape
- Batch Dimension
- Input Channel
- Output Channel
- Kernel Height
- Kernel Width

### 02.6 Stride

- Stride = 1
- Stride = 2
- Horizontal Stride
- Vertical Stride
- Downsampling

### 02.7 Padding

- Valid Padding
- Same Padding
- Zero Padding
- Padding Size
- Output Size

### 02.8 Dilation

- Dilation = 1
- Dilation > 1
- Effective Kernel Size
- Dilated Convolution

### 02.9 Conv Output Size

- Output Height
- Output Width
- Kernel
- Padding
- Stride
- Dilation

### 02.10 Conv 参数量

- Kernel Parameters
- Bias Parameters
- Parameter Count
- MAC
- FLOPs

## 03. 卷积类型

### 03.1 Standard Convolution

### 03.2 Pointwise Convolution

### 03.3 1×1 Convolution

### 03.4 Group Convolution

- Group
- Channel Partition
- Group 数量

### 03.5 Depthwise Convolution

- Channel-wise Convolution
- 每个 Channel 独立卷积
- 参数量降低

### 03.6 Depthwise Separable Convolution

- Depthwise
- Pointwise
- 与普通卷积比较

### 03.7 Dilated Convolution

### 03.8 Transposed Convolution

- Upsampling
- Output Padding
- Checkerboard Artifact

### 03.9 Dynamic Convolution

## 04. Pooling

- Max Pooling
- Average Pooling
- Global Average Pooling
- Global Max Pooling
- Kernel Size
- Stride
- Padding
- Output Shape
- Pooling vs Strided Conv

## 05. Activation

- Sigmoid
- Tanh
- ReLU
- Leaky ReLU
- PReLU
- ELU
- SELU
- GELU
- SiLU
- Swish
- Hard-Swish
- ReLU6
- Hard-Sigmoid
- Activation Range
- Saturation
- Dead ReLU

## 06. Normalization

- Normalization 基本思想

### Batch Normalization

- Mean
- Variance
- Gamma
- Beta
- Running Mean
- Running Variance
- Training
- Inference

### Layer Normalization

### Instance Normalization

### Group Normalization

### BatchNorm Folding

## 07. CNN 基本模块

- Conv Block
- Conv + Bias
- Conv + ReLU
- Conv + BN
- Conv + BN + ReLU
- Downsampling Block
- Upsampling Block
- Residual Block
- Bottleneck Block
- Inverted Bottleneck
- Feature Extraction Block

## 08. Residual Network

- Residual Learning
- Skip Connection
- Identity Mapping
- Residual Function
- BasicBlock
- Bottleneck
- Projection Shortcut
- Pre-Activation ResNet
- Gradient Flow

## 09. CNN 经典架构

- LeNet
- AlexNet
- VGG

### GoogLeNet

- Inception
- Inception Module
- Multi-branch

### ResNet

### ResNeXt

### DenseNet

- Dense Connection
- Feature Reuse

### MobileNet

- MobileNetV1
- MobileNetV2
- MobileNetV3

### ShuffleNet

### EfficientNet

### RegNet

### ConvNeXt

## 10. CNN 的空间层级

### Low-level Feature

- Edge
- Corner
- Texture

### Mid-level Feature

- Shape
- Part
- Pattern

### High-level Feature

- Object
- Semantic Feature

- Receptive Field
- Effective Receptive Field
- Feature Resolution
- Feature Channel

## 11. 下采样与上采样

- Strided Convolution
- Pooling

### Interpolation

- Nearest
- Bilinear
- Bicubic

- Transposed Convolution
- Pixel Shuffle
- Resize
- Feature Pyramid
- Multi-scale Feature

## 12. CNN 训练

- Dataset
- DataLoader
- Batch
- Epoch
- Iteration
- Forward
- Loss
- Backward
- Gradient
- Optimizer
- Learning Rate
- Learning Rate Schedule
- Weight Decay
- Momentum
- Adam
- SGD
- Dropout
- Data Augmentation
- Overfitting
- Underfitting
- Regularization
- Early Stopping

## 13. CNN Loss

- MSE
- MAE
- Cross Entropy
- Binary Cross Entropy
- Focal Loss
- Dice Loss
- IoU Loss
- Task-specific Loss

## 14. CNN 分类

- Image Classification
- Binary Classification
- Multi-class
- Multi-label
- Logits
- Softmax
- Top-1
- Top-5
- Accuracy
- Precision
- Recall
- F1

## 15. Object Detection

- Bounding Box
- Center
- Width
- Height
- IoU
- NMS
- Confidence
- Anchor
- Anchor Box
- Anchor-free
- One-stage
- Two-stage
- R-CNN
- Fast R-CNN
- Faster R-CNN
- SSD
- YOLO
- FPN

## 16. Segmentation

- Semantic Segmentation
- Instance Segmentation
- Panoptic Segmentation
- FCN
- U-Net
- Encoder
- Decoder
- Skip Connection
- DeepLab
- ASPP
- Feature Pyramid

## 17. CNN 性能分析

- Parameter
- MAC
- FLOP
- FLOPs
- Compute
- Memory
- Activation Memory
- Weight Memory
- Intermediate Tensor
- Memory Bandwidth
- Compute Bound
- Memory Bound
- Arithmetic Intensity
- Latency
- Throughput

## 18. CNN 算子视角

- Conv
- DepthwiseConv
- GroupConv
- MatMul
- Add
- Mul
- ReLU
- Sigmoid
- Pool
- BatchNorm
- LayerNorm
- Resize
- Concat
- Split
- Reshape
- Transpose
- Pad

## 19. CNN 算子实现

- Direct Convolution
- im2col
- GEMM-based Conv
- Winograd
- FFT Convolution
- Kernel
- Tiling
- Blocking
- Vectorization
- SIMD
- Memory Access

## 20. CNN 模型优化

### Operator Fusion

- Conv + BN
- Conv + Activation
- Conv + BN + Activation

- Constant Folding
- Dead Node Elimination
- Layout Optimization
- Memory Reuse
- Kernel Selection
- Graph Optimization
- Pruning
- Distillation
- Quantization

## 21. CNN 端侧部署

### Model Export

- PyTorch
- ONNX
- Intermediate Representation

- Model Conversion
- Graph
- Graph Optimization
- Operator Support
- Operator Mapping
- Hardware Partition
- CPU Backend
- GPU Backend

### NPU Backend

### Quantization

- FP32
- FP16
- INT8
- INT4
- PTQ
- QAT
- Per-tensor
- Per-channel
- Symmetric / Asymmetric

### Compilation

- Graph Compilation
- Operator Lowering
- Kernel Selection
- Code Generation
- Hardware-specific Optimization

### Runtime

- Tensor Allocation
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
