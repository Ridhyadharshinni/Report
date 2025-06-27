# Waste Classification and Segmentation System
A dual-model deep learning system for:
1. Waste Classification (MobileNetV2-based) - Categorizing waste into 6 classes
2. Material Segmentation (DeepLabV3-based) - Identifying metal types in waste

# Key Features 
- real-time waste classification using deep learning
- Web-based user interface for easy interaction
- Support for common image formats (PNG, JPG, JPEG)
- Instant classification results with visual feedback
# Classification Model (High Accuracy)
- MobileNetV2 backbone with transfer learning
- Advanced data augmentation
- Class weight balancing for imbalanced datasets
- Achieves >80% validation accuracy

# Segmentation Model (Experimental)
- DeepLabV3 with ResNet50 backbone
- Material identification (Copper, Aluminium, Iron, Others)
- Currently under development (lower accuracy)
- Provides pixel-level segmentation maps
# Prerequisites
- Python 3.8+
- NVIDIA GPU (recommended)
- CUDA 11.2+
- cuDNN 8.1+
- DeepLabV3_Resnet50
# Dataset Preparation
merged_dataset/
├── train/
│   ├── images/   
│   └── labels/  # contains .txt  
├── valid/
│   ├── images/
│   └── labels/
└── test/
    ├── images/
    └── labels/

# Dataset 
It is a Combination of two datasets
1.	https://universe.roboflow.com/wennovates/garbage-classification-arw1f/dataset/1
2.	https://universe.roboflow.com/chkkim/scrap-metal_4_1/dataset/1

