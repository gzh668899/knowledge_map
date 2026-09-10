# 深度学习基础知识地图

## 1. 人工智能基础
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Supervised Learning
- Unsupervised Learning
- Semi-Supervised Learning
- Self-Supervised Learning
- Reinforcement Learning
- Training
- Inference
- Model
- Dataset
- Sample
- Feature
- Label

## 2. 数学基础
- 标量
- 向量
- 矩阵
- 张量
- 向量运算
- 矩阵运算
- 矩阵乘法
- 点积
- 转置
- 逆矩阵
- 范数
- L1 Norm
- L2 Norm
- 概率
- 条件概率
- 随机变量
- 期望
- 方差
- 协方差
- 均值
- 标准差

## 3. 微积分基础
- 函数
- 极限
- 导数
- 偏导数
- 全导数
- 梯度
- 梯度向量
- Jacobian
- Hessian
- 链式法则
- 方向导数
- 梯度下降

## 4. 神经网络基础
- Neuron
- Neural Network
- Input
- Weight
- Bias
- Parameter
- Activation
- Layer
- Hidden Layer
- Output Layer
- Network Depth
- Network Width
- Fully Connected Layer
- Forward Propagation
- Backward Propagation

## 5. 神经元
- 神经元结构
- 加权求和
- Bias
- Activation Function
- Linear Neuron
- Nonlinear Neuron
- 参数
- 可学习参数

## 6. 激活函数
- Activation Function
- Linear
- Sigmoid
- Tanh
- ReLU
- Leaky ReLU
- PReLU
- ELU
- GELU
- SiLU
- Softmax

### 激活函数性质
- 非线性
- 饱和
- 梯度
- 梯度消失
- 梯度爆炸
- 数值稳定性

## 7. 前向传播
- Forward Pass
- Input
- Layer
- Weight
- Bias
- Activation
- Intermediate Result
- Output
- Computational Graph
- Forward Computation

## 8. 损失函数
- Loss Function
- Objective Function
- Error
- Training Loss
- Validation Loss
- Test Loss

### 常见 Loss
- MSE
- MAE
- Smooth L1
- Binary Cross Entropy
- Cross Entropy
- Negative Log Likelihood
- KL Divergence
- Cosine Loss

### Loss 相关概念
- Loss Landscape
- Global Minimum
- Local Minimum
- Saddle Point
- Optimization Objective

## 9. 反向传播
- Backpropagation
- Gradient
- Partial Derivative
- Chain Rule
- Error Propagation
- Gradient Propagation
- Parameter Gradient
- Weight Gradient
- Bias Gradient
- Computational Graph
- Automatic Differentiation

## 10. 自动微分
- Automatic Differentiation
- Autograd
- Computational Graph
- Forward Mode
- Reverse Mode
- Gradient Tracking
- Gradient Accumulation
- Detach
- Stop Gradient
- Requires Grad

## 11. 参数学习
- Parameter
- Weight
- Bias
- Learnable Parameter
- Parameter Update
- Gradient
- Learning Rate
- Optimization
- Gradient Descent

## 12. 梯度下降
- Gradient Descent
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent
- Learning Rate
- Gradient
- Parameter Update
- Convergence
- Divergence

## 13. 优化器
- Optimizer
- SGD
- Momentum
- Nesterov Momentum
- AdaGrad
- RMSProp
- Adam
- AdamW
- Learning Rate
- Weight Decay
- Momentum
- Beta
- Epsilon

## 14. 学习率
- Learning Rate
- Initial Learning Rate
- Learning Rate Schedule
- Learning Rate Decay
- Warmup
- Cosine Annealing
- Step Decay
- Exponential Decay
- One Cycle
- Adaptive Learning Rate

## 15. Batch / Epoch / Iteration
- Dataset
- Batch
- Mini-Batch
- Batch Size
- Iteration
- Step
- Epoch
- Training Step
- Gradient Accumulation
- Shuffle

## 16. 数据集
- Dataset
- Training Set
- Validation Set
- Test Set
- Sample
- Feature
- Label
- Data Distribution
- Data Preprocessing
- Data Augmentation
- Data Normalization
- Data Shuffling

## 17. 数据预处理
- Normalization
- Standardization
- Mean
- Variance
- Standard Deviation
- Min-Max Scaling
- Feature Scaling
- Data Cleaning
- Missing Data
- Outlier
- Data Augmentation

## 18. 模型训练流程
- Dataset
- Data Preprocessing
- Batch
- Forward
- Prediction
- Loss
- Backward
- Gradient
- Optimizer
- Parameter Update
- Epoch
- Validation
- Checkpoint

## 19. 模型评估
- Evaluation
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC
- AUC
- Top-1 Accuracy
- Top-5 Accuracy
- Mean Squared Error
- Mean Absolute Error

## 20. 泛化能力
- Generalization
- Generalization Error
- Training Error
- Validation Error
- Test Error
- Overfitting
- Underfitting
- Bias
- Variance
- Bias-Variance Tradeoff

## 21. 过拟合与欠拟合
- Overfitting
- Underfitting
- Model Complexity
- Training Error
- Validation Error
- Regularization
- Early Stopping
- Data Augmentation
- Dropout
- Weight Decay

## 22. 正则化
- Regularization
- L1 Regularization
- L2 Regularization
- Weight Decay
- Dropout
- Early Stopping
- Data Augmentation
- Noise Injection

## 23. 参数初始化
- Weight Initialization
- Bias Initialization
- Random Initialization
- Zero Initialization
- Xavier Initialization
- He Initialization
- Kaiming Initialization
- Initialization Distribution
- Initialization Scale

## 24. Batch Normalization
- Batch Normalization
- Batch Mean
- Batch Variance
- Running Mean
- Running Variance
- Gamma
- Beta
- Training Mode
- Evaluation Mode

## 25. Normalization 基础
- Normalization
- Batch Normalization
- Layer Normalization
- Instance Normalization
- Group Normalization
- Mean
- Variance
- Standard Deviation
- Scale
- Shift
- Epsilon

## 26. Dropout
- Dropout
- Drop Probability
- Training Mode
- Evaluation Mode
- Random Mask
- Inverted Dropout

## 27. 深度学习中的数值计算
- Floating Point
- FP32
- FP16
- BF16
- Numerical Precision
- Numerical Range
- Numerical Stability
- Overflow
- Underflow
- NaN
- Inf
- Rounding Error
- Accumulation Error

## 28. 梯度问题
- Gradient Vanishing
- Gradient Exploding
- Gradient Clipping
- Gradient Norm
- Gradient Scaling
- Numerical Stability
- Saturation
- Initialization

## 29. 计算图
- Computational Graph
- Node
- Edge
- Input
- Output
- Operation
- Parameter
- Intermediate Value
- Forward Graph
- Backward Graph
- Dependency
- Gradient Graph

## 30. 模型参数
- Parameter
- Weight
- Bias
- Parameter Count
- Trainable Parameter
- Non-Trainable Parameter
- Parameter Tensor
- Parameter Sharing
- Frozen Parameter
- Fine-Tuning

## 31. 模型结构基础
- Layer
- Block
- Module
- Network
- Sequential
- Residual Connection
- Skip Connection
- Branch
- Merge
- Hierarchical Structure

## 32. 训练模式与推理模式
- Training Mode
- Evaluation Mode
- Inference Mode
- Dropout Behavior
- BatchNorm Behavior
- Gradient Tracking
- No Grad
- Parameter Update
- Frozen Model

## 33. 迁移学习
- Transfer Learning
- Pretrained Model
- Fine-Tuning
- Feature Extraction
- Frozen Layer
- Trainable Layer
- Full Fine-Tuning
- Partial Fine-Tuning

## 34. 预训练
- Pretraining
- Pretrained Model
- Self-Supervised Learning
- Pretraining Dataset
- Pretraining Objective
- Fine-Tuning
- Downstream Task

## 35. 深度学习任务
- Classification
- Regression
- Detection
- Segmentation
- Generation
- Ranking
- Recommendation
- Representation Learning

## 36. 模型训练稳定性
- Convergence
- Loss Oscillation
- Gradient Explosion
- Gradient Vanishing
- Learning Rate
- Initialization
- Normalization
- Gradient Clipping
- Numerical Stability

## 37. 模型容量
- Model Capacity
- Parameters
- Depth
- Width
- Expressiveness
- Model Complexity
- Representation Capacity

## 38. 表征学习
- Representation Learning
- Feature Representation
- Embedding
- Latent Representation
- Feature Space
- Latent Space
- Distributed Representation
- Learned Feature

## 39. 深度学习核心概念关系

```
Input
↓
Neural Network
↓
Forward Propagation
↓
Prediction
↓
Loss
↓
Backpropagation
↓
Gradient
↓
Optimizer
↓
Parameter Update
↓
Repeat
↓
Model Convergence
```

## 40. 深度学习基础学习阶段

### 第一阶段：数学
- 标量
- 向量
- 矩阵
- 张量
- 矩阵乘法
- 概率
- 统计
- 导数
- 偏导数
- 梯度
- 链式法则

### 第二阶段：神经网络
- Neuron
- Weight
- Bias
- Layer
- Activation
- Parameter
- Forward
- Loss

### 第三阶段：训练
- Backpropagation
- Gradient
- Gradient Descent
- Optimizer
- Learning Rate
- Batch
- Epoch
- Iteration

### 第四阶段：训练问题
- Overfitting
- Underfitting
- Regularization
- Dropout
- Normalization
- Gradient Vanishing
- Gradient Exploding
- Initialization

### 第五阶段：深入
- Computational Graph
- Automatic Differentiation
- Numerical Stability
- Optimization
- Generalization
- Representation Learning
- Model Capacity
- Transfer Learning
- Pretraining
- Fine-Tuning
