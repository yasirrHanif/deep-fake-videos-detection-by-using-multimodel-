# Deep Fake Videos Detection Using Multimodal Approaches

## Overview
This repository contains a comprehensive system designed for the detection of deep fake videos utilizing a multimodal approach. This system leverages various models to analyze both visual and auditory features, improving the accuracy and reliability of detection.we achive 99.5% accuracy of fusion model of 4 different models 

## Table of Contents
- [Introduction](#introduction)
- [Models Used](#models-used)
- [Training Results](#training-results)
- [Usage Instructions](#usage-instructions)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Deepfake technology poses a significant threat by enabling the creation of highly realistic synthetic videos. The multimodal deepfake detection system aims to combat this challenge by integrating multiple models and techniques to identify such manipulations effectively.

## Models Used
1. Video Model (EfficientNet-B0): Detects facial frame inconsistencies
2.Audio Model: Analyzes speech patterns and audio anomalies
3.Metadata Analysis: Extracts digital artifacts from video files
4.Fusion Model: Combines predictions from all three approaches
## Dataset Information
1.FakeAVCeleb v1.2 dataset structure
2.Class distribution (Real vs Fake videos)
3.Data balancing strategy explanation
4.Train/validation/test split ratios

## Training Results
- Actual results from your training:
99% Accuracy on validation set
Precision/Recall/F1-scores for both classes
Training loss reduction trajectory
Confusion matrix visualization
##  Technical Stack
Python 3.11+
PyTorch with CUDA support
TorchVision & timm (EfficientNet)
OpenCV for video processing
Librosa for audio analysis
Scikit-learn for metrics

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



