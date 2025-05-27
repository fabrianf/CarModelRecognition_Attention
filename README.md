# CarModelRecognition_Attention

## Description
This project explores the impact of various attention mechanisms on car model recognition accuracy. The goal is to compare the performance of multiple architectures using pretrained weights from ImageNet and identify which attention mechanism enhances model accuracy the most or rather explore how they affect the model in their different ways.

## Architectures Compared
1. **ResNet-50** (No Attention)
2. **TResNet-L** with Efficient Channel Attention
3. **Vision Transformer (ViT)** with Self-Attention
4. **CBAM** (Convolutional Block Attention Module) with Hybrid Attention

## Objectives
- Evaluate the effectiveness of different attention mechanisms.
- Compare accuracy, training time, and inference speed.
- Determine the best model architecture for car model recognition.

## Dataset
The models were trained and evaluated using a car model dataset with images categorized by car brand and model. Pretrained weights from **ImageNet** were utilized for transfer learning.

## Results Overview
| Model               | Accuracy | Inference Time (sec) | Images/sec |
|---------------------|----------|----------------------|------------|
| ResNet-50           | 88.16%   | 0.4057               | 9954.20    |
| TResNet-L           | 90.17%   | 0.9748               | 4142.31    |
| Vision Transformer  | 81.53%   | 0.3241               | 12458.93   |
| CBAM-ResNet         | 75.80%   | 0.4426               | 9124.37    |

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-model-attention.git
   cd car-model-attention

2. Unzip image Folder in the same directory as ipynb file
   
## Acknowledgments
Pretrained weights from ImageNet
Architectures inspired by ResNet-50, TResNet-L and Vision Transformer
