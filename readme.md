

# Model Compress





## Support features



## 1.1 Training





## 1.2 Quantization

量化可以显着压缩模型的大小。 该框架支持模型PTQ和QAT（Quantization Aware Training）量化，并提供PyTorch FX量化和LSQ（Learned Step Size Quantization）量化。

### 1.2.1 PTQ



### 1.2.2 QAT



example demo resnet18

| model             | size |
| resnet18          | 44M  |
| resnet8_quantint8 | 11M  |



## 1.3 Knowledge Distillation

### 1.3.1 KD



### 1.3.2 FKD



## 1.4 pruning

