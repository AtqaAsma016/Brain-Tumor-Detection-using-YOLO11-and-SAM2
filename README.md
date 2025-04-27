# Brain Tumor Detection with YOLOv8-NAS and SAM

![Example Detection](assets/demo.gif) *(Example visualization of tumor detection and segmentation)*

##  Overview
This repository implements an advanced brain tumor detection system using:
- **YOLOv8-NAS** (Neural Architecture Search) for high-precision tumor detection
- **Segment Anything Model (SAM)** by Meta for precise tumor segmentation
- Custom-trained models on brain MRI datasets

##  Key Features
- **High Accuracy**: YOLOv8-NAS optimized for medical imaging
- **Instance Segmentation**: SAM provides pixel-level tumor masks
- **Easy Integration**: Ready-to-use inference scripts
- **Custom Training**: Code for training on your own datasets

##  Installation

### Prerequisites
- Python 3.8+
- CUDA 11.8 (for GPU acceleration)
- PyTorch 2.0
